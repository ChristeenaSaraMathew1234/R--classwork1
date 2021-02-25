# R--classwork1
 print("Hello, World!")
[1] "Hello, World!"
> 2 + 3
[1] 5
> 50000 * 42222
[1] 2111100000
> 2304 / 233
[1] 9.888412
> (33 + 44 ) * 232 / 12
[1] 1488.667
> (x <- 2 + 3)
[1] 5
> (y = x ** 4)
[1] 625
> a + 3
Error: object 'a' not found
> 5 * 9 -> a
> nummy <- c(2,3,4)
> typeof(nummy)
[1] "double"
> typeof(nummy_int)
Error in typeof(nummy_int) : object 'nummy_int' not found
> 
> typeof(nummy_int)
Error in typeof(nummy_int) : object 'nummy_int' not found
> is.numeric(nummy)
[1] TRUE
> is.numeric(nummy_int)
Error: object 'nummy_int' not found
> print("Hello, world" )
[1] "Hello, world"
> types
Error: object 'types' not found
> 
> types <- c("int","double","character")
> typeof(types)
[1] "character"
> length(types)
[1] 3
> is.numeric(types)
[1] FALSE
> is.character(types)
[1] TRUE
> logicals


> logicals <- c(TRUE,F,TRUE,T, FALSE)
> logicals
[1]  TRUE FALSE  TRUE  TRUE FALSE
> typeof(money_in_chars)
Error in typeof(money_in_chars) : object 'money_in_chars' not found
> money_in_chars <- c("20","35","33")
> typeof(money_in_chars)
[1] "character"
> money_money <- as.numeric(money_in_chars)
> money_money
[1] 20 35 33
> typeof(money_money)
[1] "double"
> money_money <- as.numeric(money_in_chars)
> money_money
[1] 20 35 33
> typeof(money_money)
[1] "double"
> new_money <- c(money_money,"33")
> new_money
[1] "20" "35" "33" "33"
> typeof(new_money)
[1] "character"
> month.abb #in-built character vector with Month Abbreviations
 [1] "Jan" "Feb" "Mar" "Apr" "May" "Jun" "Jul" "Aug" "Sep" "Oct" "Nov" "Dec"
> month.abb[2]
[1] "Feb"
> month.abb[4:7]
[1] "Apr" "May" "Jun" "Jul"
> month.abb[c(2,5,7,10)]
[1] "Feb" "May" "Jul" "Oct"
> typeof(as.logical(money_in_chars))
[1] "logical"
> money_money<-as.logical(money_in_chars)>money_money
> money_money<-as.logical(money_in_chars)
> money_money
[1] NA NA NA
> as.logical c(20,20,0)
Error: unexpected symbol in "as.logical c"
> as.logical(c(20,20.0))
[1] TRUE TRUE
> as.logical(c(20,2,0))
[1]  TRUE  TRUE FALSE
> as.logical(c(20,20,0))
[1]  TRUE  TRUE FALSE

> c(2,4,"hello" , TRUE)
[1] "2"     "4"     "hello" "TRUE" 
> c(2,4, TRUE)
[1] 2 4 1
 "c('double', 'numeric')"
> month.name
 [1] "January"   "February"  "March"     "April"     "May"       "June"      "July"      "August"    "September"
[10] "October"   "November"  "December" 
> 3:4
[1] 3 4
> 1:5
[1] 1 2 3 4 5
> seq(5,10,2)
[1] 5 7 9
> month.abb[c(7,8,12)]
[1] "Jul" "Aug" "Dec"
> days <- c("Mon","Tue","Wed")
> days
[1] "Mon" "Tue" "Wed"
> week_end <- c("Sat","Sun")
> more_days <- c(days,"Thu","Fri",week_end)
> more_days
[1] "Mon" "Tue" "Wed" "Thu" "Fri" "Sat" "Sun"
> 
