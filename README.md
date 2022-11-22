# ansible-role-win-sqlservermanagementstudio

Ansible Role to install SQL Server Management Studio on Windows

## Table of content

- [Default Variables](#default-variables)
  - [sql_server_mgmt_already_installed_path](#sql_server_mgmt_already_installed_path)
  - [sql_server_mgmt_download_url](#sql_server_mgmt_download_url)
  - [sql_server_mgmt_download_validate_certs](#sql_server_mgmt_download_validate_certs)
  - [sql_server_mgmt_extract_dir](#sql_server_mgmt_extract_dir)
  - [sql_server_mgmt_install_exe](#sql_server_mgmt_install_exe)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Default Variables

### sql_server_mgmt_already_installed_path

Path to check if already installed.

#### Default value

```YAML
sql_server_mgmt_already_installed_path: C:\Program Files (x86)\Microsoft SQL Server
  Management Studio 18\Common7\IDE\Ssms.exe
```

### sql_server_mgmt_download_url

Download URL of the package.

#### Default value

```YAML
sql_server_mgmt_download_url: https://aka.ms/ssmsfullsetup
```

### sql_server_mgmt_download_validate_certs

Validate SSL certs when downloading.

#### Default value

```YAML
sql_server_mgmt_download_validate_certs: yes
```

### sql_server_mgmt_extract_dir

Extract directory.

#### Default value

```YAML
sql_server_mgmt_extract_dir: C:\windows\temp\sqlmgmtextract
```

### sql_server_mgmt_install_exe

File name of the installation package.

#### Default value

```YAML
sql_server_mgmt_install_exe: SSMS-Setup-ENU.exe
```



## Dependencies

None.

## License

license (GPL-2.0-or-later, MIT, etc)

## Author

andif888
