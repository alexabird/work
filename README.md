- name: Remove karaf properties file
  command: rm  "{{ DDF_ETC }}/user.properties"
  when:
    - DDF_LDAP_ENABLED or DDF_USE_KEYCLOAK
  notify:
    - restart ddf
  tags:
    - ddf_reapply_config
