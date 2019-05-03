# License how-to
In this document, we describe which license we choose for our open source projects, and how to apply them.

## Choice of license

- Our license of predilection is AGPL v3 or later. See https://choosealicense.com/licenses/agpl-3.0/
- If a software needs to link with proprietary software, we must use LGPL v3 or later. See https://choosealicense.com/licenses/lgpl-3.0/
- In the case of the Kids First data resource portal, we use the Apache 2.0 license. See https://choosealicense.com/licenses/apache-2.0/

## How to apply each license
Mandatory step:

- Each project has a LICENCE.txt file. Create a text file (typically named LICENSE, or preferably LICENSE.txt) in the root of your source code and copy the text of the license into the file. See each file in the licenses directory.
- Add the contents of the boilerplate for the copyright mention to the README.md file. (see above)

Optional steps:

- Add a boilerplate notice to the top of each file. The boilerplate can be found below.
- Add `AGPL-3.0-or-later`, `LGPL-3.0-or-later` or `Apache-2.0`, depending on which one is used, to your project's package description, if applicable (e.g., Node.js, Ruby, and Rust). This will ensure the license is displayed in package directories.

Additional notes:

- Do not include the mention "All rights reserved", because some rights are reserved but not all of them. It\'s open source software.

## Boilerplates
### Boilerplate for the copyright mention in the README.md files
```
Copyright (C) 2019 Centre de recherche du CHU Sainte-Justine
See LICENCE.txt
```

### Boilerplate for AGPL v3 (or later)
This header can be put in a comment at the top of every source file in a project.
Replace the first line by a description of the project, or remove it.

```
<one line to give the program's name and a brief idea of what it does.>
Copyright (C) 2019 Centre de recherche du CHU Sainte-Justine

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published
by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
```

### Boilerplate for LGPL 3.0 (or later)
```
<one line to give the program's name and a brief idea of what it does.>
Copyright (C) 2019 Centre de recherche du CHU Sainte-Justine

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Lesser General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
```

### Boilerplate for Apache 2.0
```
Copyright 2019 Centre de recherche du CHU Sainte-Justine

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

