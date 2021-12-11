### Date Pictures

| Picture | Format   | Example                   | | Modifier  | Character | Picture |  Example  |    
| --      | --       | --                      | - | --        | --        | --      | -- |           
| @d1  | mm/dd/yy    | 12/25/21                  | | Leading   | Space     | @d2     |  1/02/2022   | 
| @d2  | mm/dd/yyyy  | 12/25/2021                | |           | Zero      | @d02    | 01/02/2022   | 
| @d3  | MMM dd,yyyy | DEC 25,2021               | |           |           |         |              | 
| @d4  | Mmmmm dd, yyyy   | December 25, 2021    | | Separator | Slash 	   | Default |  1/02/2022   |  
| @d5  | dd/mm/yy    | 25/12/21                  | |           | Period 	 | @d2.    |  1.02.2022   |
| @d6  | dd/mm/yyyy  | 25/12/2021                | |           | Comma 	   | @d2,    |  1,02,2022   |  
| @d7  | dd MMM yy   | 25 DEC 21                 | |           | Hyphen    | @d2-    |  1-02-2022   |
| @d8  | dd MMM yyyy | 25 DEC 2021               | |           | Space 	   | @d2_    |  1 02 2022   |  
| @d9  | yy/mm/dd    | 21/12/25                  | |           |           |         |              | 
| @d10 | yyyy/mm/dd  | 2021/12/25                | | Blank     | No        | @d01    | 00/00/00     | 
| @d11 | yymmdd      | 211225                    | |           | Zero      | @d01b   |              | 
| @d12 | yyyymmdd    | 20211225                  | 
| @d13 | mm/yy       | 12/21                     | 
| @d14 | mm/yyyy     | 12/2021                   | 
| @d15 | yy/mm       | 21/12                     | 
| @d16 | yyyy/mm     | 2021/12                   | 
|      |             |                           | 
| @d17 | Short Date  | 12/25/2021                | 
| @d18 | Long Date   | December 25, 2021         |

[Date Pictures in Clarion Help](https://clarion.help/doku.php?id=date_pictures.htm)

------------------------------

### Time Pictures

| Picture | Format  | Example       | | Modifier  | Character | Picture |  Example  |
| --      | --      | --          | - | --        | --        | --      | -- |       
| @t1 | hh:mm       | 12:34         | | Leading   | Space     | @t1     |  1:23    | 
| @t2 | hhmm        | 1234          | |           | Zero      | @t01    | 01:23    | 
| @t3 | hh:mmXM     | 12:34PM       | |           |           |         |          | 
| @t4 | hh:mm:ss    | 12:34:56      | | Separator | Colon 	  | Default |  1:23    | 
| @t5 | hhmmss      | 123456        | |           | Period 	  | @t1.    |  1.23    | 
| @t6 | hh:mm:ssXM  | 12:34:56PM    | |           | Comma 	  | @t1,    |  1,23    | 
|     |             |               | |           | Hyphen 	  | @t1-    |  1-23    | 
| @t7 | Short Time  | 12:34 PM      | |           | Space 	  | @t1_    |  1 23    | 
| @t8 | Long Time   | 12:34:56 PM   | |           |           |         |          | 
|     |             |               | | Blank     | No        | @t01    | 00:00    | 
|     |             |               | |           | Zero      | @t01b   |          | 

[Time Pictures in Clarion Help](https://clarion.help/doku.php?id=time_pictures.htm)
