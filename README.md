# ansible-windows-iis

## Requirements

## Role Variables

```yaml
---
# defaults file for ansible-windows-iis

windows_iis_role: []
  # - name: Web-Server
  #   include_management_tools: true
  #   include_sub_features: false
  #   state: absent
  #   subfeatures: []
  #     # - name: Web-Default-Doc
  #     #   state: present
  #     # - name: Web-Dir-Browsing
  #     #   state: present
  #     # - name: Web-Http-Errors
  #     #   state: present
  #     # - name: Web-Static-Content
  #     #   state: present
  #     # - name: Web-Http-Logging
  #     #   state: present
  #     # - name: Web-Stat-Compression
  #     #   state: present
  #     # - name: Web-Filtering
  #     #   state: present
  # - name: Web-Ftp-Server
  #   include_management_tools: true
  #   include_sub_features: false
  #   state: absent
  #   subfeatures: []

windows_iis_websites: []
  # - name: Default Web Site
  #   # ip: 192.168.250.10
  #   physical_path: c:\inetpub\wwwroot
  #   port: 80
  #   state: started
```

## Dependencies

## Example Playbook

## License

MIT

## Author Information

Larry Smith Jr.

-   [@mrlesmithjr](https://www.twitter.com/mrlesmithjr)
-   [EverythingShouldBeVirtual](http://everythingshouldbevirtual.com)
-   [mrlesmithjr.com](http://mrlesmithjr.com)
-   mrlesmithjr [at] gmail.com
