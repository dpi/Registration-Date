Registration Close
dpi@d.o - http://danielph.in

Closes Registrations on Entities 
  Entity Registrations are closed automatically, determined by the value of a 
date field attached to each entity.

Dependencies:

* Registration
* Date API

Copyright (C) 2012 Daniel Phin

## License

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License along
with this program; if not, write to the Free Software Foundation, Inc.,
51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.

## Instructions

* Attach a `date` field to an entity
* Attach a `registration` field to an entity.
* In field settings for registration field, go to 
  Registration Close -> `Close registrations on date`, and set to
  the field name of the date field attached.

## Development Notes

Entities can have more than one Registration field attached; Registration_close
will automatically use the first Registration field found on the entity.