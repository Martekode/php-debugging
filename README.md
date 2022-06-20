# php-debugging
## excersise1 
i did these together with sicko sinds i didn't understand it right away. we fixed it by giving the function a parameter.
the same value that has to be displayed.
## excersise 2 
wrong index was given so 1 changed to 0.

## excersise 3 
wrong syntax used. wrong "" .

## excersise 4 
looked up foreacht and saw the "&"-sign and added it to the loop.

## excersise 5 
i tried changing "<=" to "<" but that excluded the "z".
i also tried <= aa but that only gave me "a" in return.
so then i tried != aa and that worked
## excersise 6
this one i had a lot of trouble and asked some help from a collegue. we added the & sign again to the foreach loop. we completely ignored the randomgenerate sinds it is never called nor do we need it. implode parameters were in the wrong spot. 2 funtions echoed instead of returning. and we added -1 to the first rand method in randomHeroName(). sinds it would give a number between 0 and 2, we only need 0-1.

## excersise 7 
method parsed the wrong parameter type.
## excersise 8 
|| changed to && and you can only return one thing. if you want to return more then make an array and push them in.
## excersise 9 
hard one:
strpos returns a position (0-count($link)). knowing that we know it is going to conflict with False as it starts at the beginning of the string which is pos 0. so we have to check if the pos is > -1. also added & sign.
## excersise 10 
aso a harder one. i tried with another method but for some reason it gave me another bug so i quickly reverted. because some get deleted, $i meets it target sooner that's why car wasn't deleted. so i added +1. maybe not the best solution.
