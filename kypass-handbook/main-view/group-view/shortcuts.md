# Shortcuts

By default, some shortcuts are created above the group list.  These are just filters.

### All entries

All entries without filters.

### Expired entries

All entries with the expired flag

### Bad password

The passwords are evaluated using an algorithm for estimating their strength: 

* It checks which character set are used \(case, digits, special characters, ...\),
* Repeated characters and character differences result in penalties. 

It result in an entropy bits value:

| Bits | Strength |
| :--- | :--- |
| 0-64 | Very weak \(only for to keep out family members\) |
| 64-128 | Moderate \(ok for company passwords\) |
| ≥ 128 | Very strong \(often overkill\) |

The shortcut display all entries where the password bits &lt; 64 

### Favorites

All entries that are flagged as favorite \(slide on an entry to set it and select the hearth\)

![Flag favorite](../../../.gitbook/assets/image%20%285%29.jpeg)

