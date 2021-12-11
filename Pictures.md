### Date Pictures

| Picture | Format   | Example |
| --      | --       | --      |
| @d1  | mm/dd/yy    | 12/25/21 |
| @d2  | mm/dd/yyyy  | 12/25/2021 |
| @d3  | MMM dd,yyyy | DEC 25,2021 |
| @d4  | Mmmmm dd, yyyy   | December 25, 2021 |
| @d5  | dd/mm/yy    | 25/12/21 |
| @d6  | dd/mm/yyyy  | 25/12/2021 |
| @d7  | dd MMM yy   | 25 DEC 21 |
| @d8  | dd MMM yyyy | 25 DEC 2021 |
| @d9  | yy/mm/dd    | 21/12/25 |
| @d10 | yyyy/mm/dd  | 2021/12/25 |
| @d11 | yymmdd      | 211225 |
| @d12 | yyyymmdd    | 20211225 |
| @d13 | mm/yy       | 12/21 |
| @d14 | mm/yyyy     | 12/2021 |
| @d15 | yy/mm       | 21/12 |
| @d16 | yyyy/mm     | 2021/12 |
| | | |
| @d17 | Short Date  | 12/25/2021 |
| @d18 | Long Date   | December 25, 2021 |

#### Date Picture Modifiers
| Type      | Character | Picture |  Example  |
| --        | --        | --      | -- |
| Leading   | Space     | @d2     |  1/02/2022   |
|           | Zero      | @d02    | 01/02/2022   |
|           |           |         |              |
| Separator | Slash 	  | Default |  1/02/2022   |
|           | Period 	  | @d2.    |  1.02.2022   |
|           | Comma 	  | @d2,    |  1,02,2022   |
|           | Hyphen 	  | @d2-    |  1-02-2022   |
|           | Space 	  | @d2_    |  1 02 2022   |
|           |           |         |              |
| Blank     | No        | @d01    | 00/00/00     |
|           | Zero      | @d01b   |              |

======================================================

### Time Pictures

| Picture | Format  | Example |
| --      | --      | --      |
| @t1 | hh:mm       | 12:34 |
| @t2 | hhmm        | 1234 |
| @t3 | hh:mmXM     | 12:34PM |
| @t4 | hh:mm:ss    | 12:34:56 |
| @t5 | hhmmss      | 123456 |
| @t6 | hh:mm:ssXM  | 12:34:56PM |
|     | | |
| @t7 | Short Time  | 12:34 PM |
| @t8 | Long Time   | 12:34:56 PM |

#### Time Picture Modifiers

| Type      | Character | Picture |  Example  |
| --        | --        | --      | -- |
| Leading   | Space     | @t1     |  1:23    |
|           | Zero      | @t01    | 01:23    |
|           |           |         |          |
| Separator | Colon 	  | Default |  1:23    |
|           | Period 	  | @t1.    |  1.23    |
|           | Comma 	  | @t1,    |  1,23    |
|           | Hyphen 	  | @t1-    |  1-23    |
|           | Space 	  | @t1_    |  1 23    |
|           |           |         |          |
| Blank     | No        | @t01    | 00:00    |
|           | Zero      | @t01b   |          |
