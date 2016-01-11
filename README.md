# cbora12ccl-cookbook

Install Oracle 12c Client on a Linux 64 bit machine

## Supported Platforms

Linux - RHEL

## Attributes --> See attributes file

<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt></tt></td>
    <td>Boolean</td>
    <td></td>
    <td><tt></tt></td>
  </tr>
</table>

## Usage

### cbora12ccl::default

Include `cbora12ccl` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[cbora12ccl::default]",
    "recipe[cbora12ccl::oracle_users_groups_dirs_unix]",
    "recipe[cbora12ccl::oracle_client_install_12c]"
  ]
}
```

## License and Authors

Author:: Gowrish Mallipattana
