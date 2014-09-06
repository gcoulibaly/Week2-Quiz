Week2-Quiz
==========

#1, creating numeric vector
 v<-rep(1:5,4)
 v
 [1] 1 2 3 4 5 1 2 3 4 5 1 2 3 4 5 1 2 3 4 5
 #2 changing numeric vector into character
 c<-as.character(v)
 c
 [1] "1" "2" "3" "4" "5" "1" "2" "3" "4" "5" "1" "2"
 [13] "3" "4" "5" "1" "2" "3" "4" "5"
 #3 changing numeric vector into factor vector
 f<-factor(v)
 f
 [1] 1 2 3 4 5 1 2 3 4 5 1 2 3 4 5 1 2 3 4 5
 Levels: 1 2 3 4 5
 #5 number of levels that the vector has
 l<nlevels(f)
 Error: object 'l' not found
 l<-nlevels(f)
 l
 [1] 5
 #5 Creating vector with a formula, sapply
 r<-sapply(v, function(x) 3*x^2-4*x +1)
 r
 [1] 0 5 16 33 56 0 5 16 33 56 0 5 16 33 56 0
 [17] 5 16 33 56
 #6 Creating a named list
 #7 Creating a named list
 v=list(gender=c(1,2), status=c("single","married"))
 v
 $gender
 [1] 1 2

$status
 [1] "single" "married"


v[["gender"]]
 [1] 1 2
 v$gender
 [1] 1 2
