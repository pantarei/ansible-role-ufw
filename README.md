Ansible Role for UFW
====================

[![Build Status](https://travis-ci.org/pantarei/ansible-role-ufw.svg?branch=master)](https://travis-ci.org/pantarei/ansible-role-ufw)
 [![GitHub tag](https://img.shields.io/github/tag/pantarei/ansible-role-ufw.svg)](https://github.com/pantarei/ansible-role-ufw)
 [![GitHub license](https://img.shields.io/github/license/pantarei/ansible-role-ufw.svg)](https://github.com/pantarei/ansible-role-ufw/blob/master/LICENSE)
 [![Ansible Role](https://img.shields.io/ansible/role/6152.svg)](https://galaxy.ansible.com/detail#/role/6152)

Ansible Role for UFW Management.

Requirements
------------

This role require Ansible 1.9 or higher.

This role was designed for Ubuntu Server 14.04 LTS.

Role Variables
--------------

<table>
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">parameter</th>
<th align="left">required</th>
<th align="left">default</th>
<th align="left">choices</th>
<th align="left">comments</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">ufw_name</td>
<td align="left">yes</td>
<td align="left">example</td>
<td align="left"></td>
<td align="left">pass value as <code>name</code> to <a href="http://docs.ansible.com/ansible/ufw_module.html">ufw module</a>.</td>
</tr>
</tbody>
</table>

Dependencies
------------

No additional role dependencies.

Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: hswong3i.ufw, ufw_name: 'www1' }

License
-------

-   Code released under [MIT](https://github.com/hswong3i/ansible-role-ufw/blob/master/LICENSE)
-   Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

Author Information
------------------

-   Wong Hoi Sing Edison
    -   <https://twitter.com/hswong3i>
    -   <https://github.com/hswong3i>

