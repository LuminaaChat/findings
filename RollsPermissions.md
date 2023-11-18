# UserRolls/Permissions

## Permissions

|abbreviation|description|hint
|----|----|----
|C|Create
|D|Delete
|R|Read
|E|Export
|M|Mute
|P|Pin|Messages only
|X|Forbidden

## Assignments

|Roll/Object | Messages|(Group)-Chat|Group-Users|Groups|Users|Archive|Contacts
|----|----|----|----|----|----|----|----
|**User-Client**|C,R|R|R|-|-|X|-
|**User-Employee**|C,D,R,P (assigned)|R,E*|R,M|-|-|X|R
|**User-Leg.Guardian**|C,R|R|R|-|-|X|-
|**Admin-Tech**|X|C,D|C,D,R|C,D,R,E|C,D,R,E|X|C,D,R
|**Admin-Functional**|C,D,R,P (all)|R,E|R,M|R|R|X|R
|**root**|X|C,D,R|C,D,R|C,D,R|C,D,R|R,E|C,D,R
