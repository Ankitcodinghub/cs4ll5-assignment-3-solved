# cs4ll5-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CS4LL5 Assignment 3 Solved](https://www.ankitcodinghub.com/product/cs4ll5-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95713&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS4LL5 Assignment 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
This is a worked example showing convergence of EM training with IBM model 1. The pairs are

s1 la maison s2 la fleur

o1 the house o2 the flower

To apply the brute force EM algorithm, for each pair, each of its possible alignments has to be considered. Including the possibility of aligning positions in o with NULL, there are 32 = 9 possibilities. To save a little in the pencil-and-paper calculations, we will consider a version which does not allow aligning positions in o with NULL. In this case, there are 22 = 4 possibilities:

la ma la ma la ma la ma the ho the ho the ho the ho

la fl la fl la fl la fl

the flo the flo the flo the flo

use a1 . . . a14 for the 4 possible alignments between o1 and s1 use a21 . . . a24 for the 4 possible alignments between o2 and s2

table shows translations probabilites, with tr(o|s) shown at row o, col s, and they are all ini- tialised to 1

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
<div class="layoutArea">
<div class="column">
tr(o|s) la ma f l

111 333

111 333

111 333

</div>
</div>
<div class="layoutArea">
<div class="column">
the

ho

flo

</div>
</div>
<div class="layoutArea">
<div class="column">
To execute the brute force EM algorithm we need first for the pairs o1, s1 and o2, s2 to determine theconditionalalignmentprobabilitiessop(a|o1,s1)andp(a|o2,s2). Theslidesgaveaderivation of the formula for p(a|o, s), it came out to be

􏰌j [p(oj |sa(j))]

p(a|o,s) = 􏰋a′ 􏰌j[p(oj|sa′(j))] (1)

and in the derivation 1 terms cancelled. In the corresponding derivation disallowing (ls +1)lo

alignments to NULL, there will instead be a cancellation of 1 terms, and exactly the same (ls )lo

formula for the conditional alignment probability (1) will be derived. As a name for the numerator term in (1) we will use num(a)

So to determine the p(a|o, s) values for each pair we need to

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
1. for each possible a determine num(a) (ie. 􏰌j[p(oj|sa(j))])

2. sum these to give the denominator 􏰋a num(a) and then take ratios

Armed with these conditional probabilities can then compute expected counts of o, s combina- tions across the corpus, and from these recalculate tr(o|s) probabilities.

</div>
</div>
<div class="layoutArea">
<div class="column">
ITERATION 1

considering the first pair, for each a1n calculate num(a1n): n u m ( a 1 1 ) n u m ( a 12 ) n u m ( a 13 )

= 1 1 ditto ditto 33

sim. for each a2 calculate num(a2 ). At this stage, these all work out as 1 . nn9

from these to calculate the conditional probabilities P(adn|o,s), need to sum the num(an) by summing across the table and use it as denominator ie.

</div>
</div>
<div class="layoutArea">
<div class="column">
n u m ( a 14 ) ditto

</div>
</div>
<div class="layoutArea">
<div class="column">
=1 9

</div>
</div>
<div class="layoutArea">
<div class="column">
P(adn|od,sd) = 􏰋num(adn)

n′ num(adn′)

</div>
</div>
<div class="layoutArea">
<div class="column">
P (a1|o1, s1) = 1/9

4×1/9 =1

4

P (a21|o2, s2) = 1/9

4×1/9 =1

4

</div>
<div class="column">
P (a12|o1, s1) ditto

P (a2|o2, s2) ditto

</div>
<div class="column">
P (a13|o1, s1) ditto

P (a23|o2, s2) ditto

</div>
<div class="column">
P (a14|o1, s1) ditto

P (a24|o2, s2) ditto

</div>
</div>
<div class="layoutArea">
<div class="column">
Notice these numbers make intuitive sense: with all tr(o|s) set equal, all alignments should be equally probable, giving a value of 1 for each.

4

Now for each possible vocabulary combination o,s combination we have to make a count by going through all the alignments and incrementing the count by how many times o is paired with s in the alignment and multiplying that by the above conditional alignment probabilities

For these short sentences the o, s count for any alignment is at most 1, and it will be handy for the calculations to note for each (o, s) the alignments where it occurs once1

la ma fl

</div>
</div>
<div class="layoutArea">
<div class="column">
2:– based on this we get the following expected counts

</div>
<div class="column">
2:2 4

</div>
</div>
<div class="layoutArea">
<div class="column">
the 1:1 2 2:1 2

ho 1:1 3 2:–

</div>
<div class="column">
1:3 4 1:–

</div>
</div>
<div class="layoutArea">
<div class="column">
flo 1:– 2:1 3

</div>
<div class="column">
1:2 4 1:– 2:– 2:–

1:– 1:–

</div>
</div>
<div class="layoutArea">
<div class="column">
2:–

</div>
<div class="column">
2:3 4

</div>
</div>
<div class="layoutArea">
<div class="column">
1to read this table the (ho,la) entry has 1:1 3 to indicate in first pair (o1,s1), the (ho,la) pairing occurs 2:–

in alignments a1 and a13, and the pairing never occurs in the alignments for the second pair

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
cnt la ma fl the 4×1 2×1 2×1

ho2×12×1 0 44

flo2×1 0 2×1 44

and for these counts get new tr(o|s) by normalising by column sums

</div>
</div>
<div class="layoutArea">
<div class="column">
444

</div>
</div>
<div class="layoutArea">
<div class="column">
tr(o|s) la ma f l

42

flo 1 0 1 42

</div>
</div>
<div class="layoutArea">
<div class="column">
111 222

</div>
</div>
<div class="layoutArea">
<div class="column">
the

ho 1 1 0

</div>
</div>
<div class="layoutArea">
<div class="column">
ITERATION 2

</div>
</div>
<div class="layoutArea">
<div class="column">
using new tr(o|s) value re-calculate for each a1n, num(a1n), and for each a2n, num(a2n):

n u m ( a 1 1 ) n u m ( a 12 ) n u m ( a 13 ) n u m ( a 14 ) 11111111

2 41 2 22 2 41 2 22

=8=8=8=8

n u m ( a 21 ) n u m ( a 2 2 ) n u m ( a 23 ) n u m ( a 24 ) 11111111

2 41 2 22 2 41 2 22

=8=8=8=8 then re-calculate the conditional probabilities P (a|o, s).

P (a1|o1, s1) P (a12|o1, s1) P (a13|o1, s1) P (a14|o1, s1) 1111 6363

P (a21|o2, s2) P (a2|o2, s2) P (a23|o2, s2) P (a24|o2, s2) 1111 6363

then re-calculate the expected counts of o, s combinations as shown in the table below (eg. the expected count for (the,la) is coming from a1, a12, a21, a2)

</div>
</div>
<div class="layoutArea">
<div class="column">
cnt the

626 646 =6 =6

flo 1+1 0 2+2 626 646

=6 =6

and for these counts get new tr(o|s) by normalising by column sums

</div>
</div>
<div class="layoutArea">
<div class="column">
la ma fl

</div>
</div>
<div class="layoutArea">
<div class="column">
1+2+ 1+2 1+2 666666

</div>
</div>
<div class="layoutArea">
<div class="column">
1+2 =3 =3 66666

</div>
</div>
<div class="layoutArea">
<div class="column">
=6

ho1+12+2 0

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
tr(o|s) la ma f l

57

flo 1 0 4 57

</div>
</div>
<div class="layoutArea">
<div class="column">
333 577

</div>
</div>
<div class="layoutArea">
<div class="column">
the

ho 1 4 0

</div>
</div>
<div class="layoutArea">
<div class="column">
ITERATION 3

</div>
</div>
<div class="layoutArea">
<div class="column">
using new tr(o|s) value re-calculate for each a1n, num(a1n) and each a2n, num(a2n):

num(a1) num(a12) num(a13) num(a14 ) 31343134 55577577

n u m ( a 21 ) n u m ( a 2 2 ) n u m ( a 23 ) n u m ( a 24 ) 31343134 55577577

then re-calculate the conditional probabilities P (a|o, s).

</div>
</div>
<div class="layoutArea">
<div class="column">
P (a1|o1, s1) 0.1512

P (a21|o2, s2) 0.1512

</div>
<div class="column">
P (a12|o1, s1) 0.4321

P (a2|o2, s2) 0.4321

</div>
<div class="column">
P (a13|o1, s1) P (a14|o1, s1) 0.1080 0.3086

P (a23|o2, s2) P (a24|o2, s2) 0.1080 0.3086

</div>
</div>
<div class="layoutArea">
<div class="column">
then re-calculate the expected counts of o, s combinations

cnt la ma fl

</div>
</div>
<div class="layoutArea">
<div class="column">
the 0.1512 + 0.4321 + 0.1512 +

0.4321 = 1.167

ho 0.1512 + 0.1080

</div>
<div class="column">
0.1080 + 0.3086 = 0.4167

0.4321 +

</div>
<div class="column">
0.1080 + 0.3086 = 0.4167

0

0.4321 +

</div>
</div>
<div class="layoutArea">
<div class="column">
0.3086 ==

</div>
</div>
<div class="layoutArea">
<div class="column">
0.2593 flo 0.1512 +

</div>
<div class="column">
0.7407 0

</div>
</div>
<div class="layoutArea">
<div class="column">
0.1080 == 0.2593 0.7407

and for these counts get new tr(o|s) by normalising by column sums tr(o|s) la ma fl

the 0.6923 0.36 0.36 ho 0.1538 0.64 0

f lo 0.1538 0 0.64

Over the 3 iterations, tr(the|la), tr(ho|ma) and tr(flo|fl) are steadily increasing.

If the calculations are carried on, after 10 iterations you have the following for the translation probabilities

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
<div class="layoutArea">
<div class="column">
0.3086

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
ho f lo

this is the history over the 10 iterations

</div>
<div class="column">
0.904 0

0 0.904

o|s at each iteration

</div>
</div>
<div class="layoutArea">
<div class="column">
In the end the tr(o|s) table converges to:

</div>
</div>
<div class="layoutArea">
<div class="column">
tr(o|s) la ma f l the 0.982 0.096 0.096

</div>
</div>
<div class="layoutArea">
<div class="column">
0.009 0.009

1 2 3

0.5 0.6 0.69 0.77 0.84 0.25 0.2 0.15 0.11 0.081 0.25 0.2 0.15 0.11 0.081

</div>
</div>
<div class="layoutArea">
<div class="column">
Obs the house flower the house flower the house flower

</div>
<div class="column">
Src 0

la 0.33 la 0.33 la 0.33 maison 0.33 maison 0.33 maison 0.33 fleur 0.33 fleur 0.33 fleur 0.33

</div>
<div class="column">
4 5

</div>
<div class="column">
6 7 0.89 0.93 0.056 0.037 0.056 0.037 0.2 0.16 0.8 0.84 0.00 0.00 0.2 0.16 0.00 0.00 0.8 0.84

</div>
<div class="column">
8 9 10 0.95 0.97 0.98 0.024 0.015 0.009 0.024 0.015 0.009 0.14 0.11 0.096 0.86 0.89 0.9 0.00 0.00 0 0.14 0.11 0.096 0.00 0.00 0 0.86 0.89 0.9

</div>
</div>
<div class="layoutArea">
<div class="column">
0.5 0.43 0.36 0.5 0.57 0.64 0.00 0.00 0.00 0.5 0.43 0.36 0.00 0.00 0.00 0.5 0.57 0.64

</div>
<div class="column">
0.3 0.24 0.7 0.76 0.00 0.00 0.3 0.24 0.00 0.00 0.7 0.76

</div>
</div>
<div class="layoutArea">
<div class="column">
tr(o|s) la ma

the 1 0 0 ho 0 1 0 flo 0 0 1

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
