# [medisys-dbms-change][103]


```bash
:'
/opt/path/medisys-dbms-change/
  ├─ README.md
  ├─ pom.xml
  ├─ src
  │   ├─ test/
  │   │   ├─ java
  │   │   │   ├─ my.com.medisys.boot/BootstrapApplication.java
  │   │   │   ├─ my.com.medisys.config/package-info.java
  │   │   │   └─ my.com.medisys.dbms.change.test/ChangeTests.java
  │   │   └─ resources/
  │   │       ├─ log4j.xml
  │   │       ├─ application.properties
  │   │       ├─ liquibase
  │   │       │   ├─ dev.properties
  │   │       │   ├─ dif.properties
  │   │       │   ├─ pro.properties
  │   │       │   └─ syn.properties
  │   │       ├─ schema/
  │   │       │   ├─ hr_all_ini.md
  │   │       │   ├─ hr_all_ini.sql
  │   │       │   ├─ hr_dev_bas_ini.sql
  │   │       │   ├─ hr_dev_dif_add.sql
  │   │       │   └─ hr_dev_dif_rev.sql
  │   │       └─ change/
  │   └─ main/
  │       ├─ java/my.com.medisys.dbms.change/package-info.java
  │       └─ resources/META-INF/migrations/
  │           ├─ db.changelog-master.xml
  │           ├─ config/
  │           │   ├─ db.changelog-config.xml
  │           │   ├─ db.changelog-property.xml
  │           │   └─ db.changelog-restrict.xml
  │           └─ change/
  │               ├─ db.changelog-V0.xml
  │               └─ V0/
  │                   ├─ db.changelog-V0.0.xml
  │                   └─ V0.0/
  │                       ├─ db.changelog-V0.0.00.xml
  │                       └─ V0.0.00/
  │                           ├─ db.changelog-V0.0.00_20180801_110011.xml
  │                           ├─ db.changelog-V0.0.00_20180802_110011.xml
  │                           ├─ db.changelog-V0.0.00_20180803_110011.xml
  │                           ├─ db.changelog-V0.0.00_20180804_110011.xml
  │                           ├─ db.changelog-V0.0.00_20180805_110011.xml
  │                           ├─ db.changelog-V0.0.00_20180806_110011.xml
  │                           └─ 20180802_110011/
  │                               ├─ countries__dev_qac_uat_pro.csv
  │                               ├─ departments__dev_qac.csv
  │                               ├─ departments__uat_pro.csv
  │                               ├─ employees__dev_qac.csv
  │                               ├─ job_history__dev_qac.csv
  │                               ├─ jobs__dev_qac_uat_pro.csv
  │                               ├─ locations__dev_qac_uat_pro.csv
  │                               └─ regions__dev_qac_uat_pro.csv
  └─ target/
      ├─ medisys-dbms-change-0.0.00.GA.jar
      ├─ db.changelog-0.0.00_20180814_070816.xml
      └─ 20180814_070816/
          ├─ countries.csv
          ├─ departments.csv
          ├─ employees.csv
          ├─ job_history.csv
          ├─ jobs.csv
          ├─ locations.csv
          └─ regions.csv
'
```


### Database

```sql
DROP DATABASE IF EXISTS `hr_dev`;
DROP DATABASE IF EXISTS `hr_pro`;

CREATE DATABASE IF NOT EXISTS `hr_dev` DEFAULT CHARACTER SET utf8 COLLATE utf8_general_ci;
CREATE DATABASE IF NOT EXISTS `hr_pro` DEFAULT CHARACTER SET utf8 COLLATE utf8_general_ci;
```

### Contact

- [**info@medisys.com.my**][200]
- [**www.medisys.com.my**][100] 


[100]:  http://www.medisys.com.my "Medical Systems Co."
[101]:  https://github.com/ "GitHub"
[102]:  https://github.com/medisysco/medisys-dbms-parent "medisys-dbms-parent"
[103]:  https://github.com/medisysco/medisys-dbms-change "medisys-dbms-change"

[200]:  mailto:info@medisys.com.my "Medisys Contact"
[201]:  mailto:sherbini@medisys.com.my "Mohamad Al-Sherbini(Sherbini)"
[202]:  mailto:aziz@medisys.com.my "Azizul Hoque Bhuyan(Aziz)"
[203]:  mailto:shahed@medisys.com.my "Md Shahed Hossain(Shahed)"
