# Puzzle-2-Solution

<img align="center" width="600" src="https://user-images.githubusercontent.com/85172635/139573262-973a15fa-b9b8-45fe-ad72-d16fa4bcc0dc.jpg">
<br><br>
<h1>SOLUTION</h1>
Let A be the starting point and B be the destination in this transportation. If the camel is taken with 1000 bananas at start, to reach the point B which is 1000 km away from A, it needs 1000 bananas. So there will be no bananas left to return back to point A.

That's why we need to break down the journey into 3 parts.

<img align="center" width="800" src="https://user-images.githubusercontent.com/85172635/139573640-7f1bc32f-ae66-4a78-8f0a-8eb22f3e37cb.png">
<br><br>


The Camel and Banana Puzzle Solution

Part 1 :

For every 1 km the camel needs to -

1. Move ahead 1 km with 1000 bananas but eat 1 banana in a way.

2. Leave 998 bananas at the point and take 1 banana to return back to previous point.

3. Pick up another 1000 bananas and move forward while eating 1 banana.

4. Drop 998 bananas at the same point. Return back to previous point by consuming 1 banana.

5. Pick left over 1000 bananas and move 1km forward while consuming 1 banana to same point where 998 + 998 bananas are dropped. Now, the camel doesn't need to  return back to previous point. So, 998 + 998 + 999 are carried to the point.

That is for every 1km, the camel needs 5 bananas.

After 200 km from point A, the camel eats of 200x5 = 1000 bananas and at this point the part 1 ends.

-------------------------------------------------------------------------------------------------
 
PART 2 :

1. Move ahead 1 km with 1000 bananas but eat 1 banana in a way.

2. Leave 998 bananas at the point and take 1 banana to return back to previous point.

3. Pick up another 1000 bananas and move forward to the point where 998 bananas left while eating 1 banana.

Now, the camel needs only 3 bananas per km.

So for next 333 km, the camel eats up 333x3 = 999 bananas.

-------------------------------------------------------------------------------------------------
 
PART 3 :

So far, the camel has travelled 200 + 333 = 533 km from point A and needs to cover 1000 - 533 = 467 km more to reach at B.

Number of bananas left are 3000 - 1000 - 999 = 1001.

Now, instead of wasting another 3 bananas for next 1 km here, better drop 1 banana at the point P2 and move ahead to B with 1000 bananas. This time the camel doesn't need to go back at previous points & can move ahead straightaway.

For the remaining distance of 467 km, the camel eats up another 467 bananas and in the end 1000 - 467 = 533 bananas will be left.
