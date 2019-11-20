# Solutions for *enable1.txt* regex practice

 
- egrep	--color	'^x.*x$' enable1.txt 
- egrep	--color	'^(.).*x$' enable1.txt 
- egrep	--color	'^(.).*\1$' enable1.txt 
- egrep	--color	'^(..).*\1$' enable1.txt 
- egrep	--color	'^(.).\1$' enable1.txt 
- egrep	--color	'^(.)(.)\2\1$' enable1.txt 
- egrep	--color	'^(.)(.).\2\1$' enable1.txt 
- egrep	--color	'^(.)(.)(.)\3\2\1$' enable1.txt 
- egrep	--color	'^[aeiou]' enable1.txt 
- egrep	--color	'^([aeiou]).*\1$' enable1.txt 
- egrep	-c	'^([aiou]).*\1$' enable1.txt 
- egrep	--color	'^([aeiou]).*\1$' enable1.txt 
- egrep	--color	'^[aeiou]' enable1.txt 
- egrep	--color	'^[^aeiou]' enable1.txt 
- egrep	--color	'[^aeiou]' enable1.txt 
- egrep	--color	'^[j-m]' enable1.txt 
- egrep	--color	'^[aeiou]+$' enable1.txt 
- egrep	--color	'^[^aeiou]+$' enable1.txt 
- egrep	--color	'^[^aeiouy]+$' enable1.txt 
- egrep	--color	'q' enable1.txt 
- egrep	--color	'q[^u]' enable1.txt 
- egrep	--color	'suq' enable1.txt 
- egrep	--color	'q$' enable1.txt 
- egrep	--color	'qs$' enable1.txt 
- pcregrep	--color	'q(?!u)' enable1.txt 
- egrep	--color	'q$|q[^u]' enable1.txt 
- egrep	--color	'(q$)|(q[^u])' enable1.txt 
- egrep	--color	'[aeiou][aeiou][aeiou][aeiou][aeiou]'
- egrep	--color	'[aeiou][aeiou][aeiou][aeiou][aeiou]' enable1.txt 
- egrep	--color	'([aeiou])\1' enable1.txt 
- egrep	--color	'[aeiou]{5}' enable1.txt 
- egrep	--color	'[aeiou]{4}' enable1.txt 
- egrep	--color	'[aeiou]{4,}' enable1.txt 
- egrep	--color	'[aeiou]{2,3}' enable1.txt 
- egrep	--color	'[aeiou]{,3}' enable1.txt 
- egrep	--color	'[aeiou]{1,3}' enable1.txt 
- egrep	--color	'^(.*)\1$' enable1.txt 
- egrep	--color	'^(.*)\1' enable1.txt 
- egrep	--color	'^(.+)\1' enable1.txt 
- egrep	--color	'(.+)\1' enable1.txt 
- egrep	--color	'(.{3})\1' enable1.txt 
- egrep	--color	'^[^aeiou]{7,}' enable1.txt 
- egrep	--color	'^[^aeiouy]{7,}' enable1.txt 
- egrep	--color	'z' enable1.txt 
- egrep	--color	'zz' enable1.txt 
- egrep	--color	'z{2}' enable1.txt 
- egrep	--color	'(z)(.*)(z)' enable1.txt 
- egrep	--color	'z.*z' enable1.txt 
- egrep	--color	'z.*?z' enable1.txt 
- egrep	--color	'z.*z.*z' enable1.txt 
- egrep	--color	'z.*z' enable1.txt 
- egrep	--color	'z.+z' enable1.txt 
- egrep	--color	'ooo' enable1.txt 
- egrep	--color	'eee' enable1.txt 
- egrep	--color	'(.)\1\1' enable1.txt 
- egrep	--color	'r.+r' enable1.txt 
- egrep	--color	'r[^r]r' enable1.txt 
- egrep	--color	'r[^r]+r' enable1.txt 
- egrep	--color	'.{4,}' enable1.txt 
- egrep	--color	'.{1,4}' enable1.txt 
- egrep	--color	'^.{1,4}$' enable1.txt 
- egrep	--color	'[aeiou]' enable1.txt 
- egrep	--color	'^z' enable1.txt 
- egrep	--color	'^z' enable1.txt | head
- egrep	--color	'a' enable1.txt
- egrep	'a'	enable1.txt | - egrep 'e' 
- egrep	'a'	enable1.txt | - egrep 'e' | - egrep 'i' | - egrep 'o' | - egrep 'u'
- egrep	--color	'[aeiou]{2,}' enable1.txt 
- egrep	--color	'[aeiou]{2,}' enable1.txt | - egrep '.{5,}'
- egrep	--color	'[aeiou]{2,}' enable1.txt | - egrep '.{8,}'
- egrep	--color	'[aeiou]{2,}' enable1.txt | - egrep '.{12,}'