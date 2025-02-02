# dompdf-fonts

This extension adds support to unicode characters to the domPdf
extension. It is not required for drupal8+ installs which should
get the fonts when installing using composer.

[see](https://docs.civicrm.org/installation/en/latest/general/unicode_pdf/)


#  Before
![img.png](images/borked.png)

# After
![img.png](images/fixed.png)

Adds support to domPdf pdf creation for unicode characters - as

The extension is licensed under [AGPL-3.0](LICENSE.txt).

## Requirements

* PHP v7.2+
* CiviCRM 5.46

## Installation (Web UI)

Learn more about installing CiviCRM extensions in the [CiviCRM Sysadmin Guide](https://docs.civicrm.org/sysadmin/en/latest/customize/extensions/).

## Installation (CLI, Zip)

Sysadmins and developers may download the `.zip` file for this extension and
install it with the command-line tool [cv](https://github.com/civicrm/cv).

```bash
cd <extension-dir>
cv dl dompdf-fonts@https://github.com/FIXME/dompdf-fonts/archive/master.zip
```

## Installation (CLI, Git)

Sysadmins and developers may clone the [Git](https://en.wikipedia.org/wiki/Git) repo for this extension and
install it with the command-line tool [cv](https://github.com/civicrm/cv).

```bash
git clone https://github.com/FIXME/dompdf-fonts.git
cv en dompdf_fonts
```

## Getting Started

Just install the extension

## Known Issues

The documentation suggests further fonts should be added. Also, if pasting
from word then your html may reference other fonts that do not support unicode.
