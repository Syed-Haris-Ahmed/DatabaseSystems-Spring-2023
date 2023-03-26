### Step-1

```bash
docker run -d -p 1521:1521 --name ORCL-11g -e ORACLE_ALLOW_REMOTE=true wnameless/oracle-xe-11g-r2
```

### Step-2

```bash
docker cp TABLES.dmp ORCL-11g:/u01/app/oracle/admin/XE/dpdump
```

### Step-3

```bash
docker exec -it ORCL-11g bash
```

### Step-4

```bash
sqlplus sys/oracle as sysdba
```

### Step-5

```SQL
CREATE USER demo IDENTIFIED BY demo;
GRANT CONNECT,RESOURCE,DBA,UNLIMITED TABLESPACE TO demo;
EXIT
```

### Step-6

```bash
impdp system/oracle DIRECTORY=DATA_PUMP_DIR DUMPFILE=TABLES.dmp REMAP_SCHEMA=uni:demo
```

### Step-7
```bash
sqlplus demo/demo
```

