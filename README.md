Download Link: https://assignmentchef.com/product/solved-cse110-module5-brand-name-generator
<br>
The Biotech start-up you are working for is developing new drugs quicker than you can say “Certain Fungal Infections”. You have been loaned to the marketing department to develop an application that can generate candidate names for these new medications. After some initial market research, your business users have come up with the following criteria for a brand name:

<ul>

 <li>It must have at least 6 letters but no more than 12.</li>

 <li>The letters at odd positions (1, 3, 5, …) must be consonants (bcdfghjklmnprstvwxz).</li>

 <li>The letters at even positions (2, 4, 6, …) must be vowels (aeiou).</li>

 <li>The letters ‘Q’ and ‘Y’ did not “resonate positively” with the focus group and should be avoided.</li>

 <li>The first letter should be capitalized, the rest lowercase.</li>

</ul>

<ol start="2">

 <li><strong>Notes: </strong>

  <ul>

   <li>You <strong><u>must</u></strong> create a method which generates one new drug name, as follows:</li>

  </ul></li>

</ol>

String generateName(int size) { … your code here … }

The size parameter will be used to create a generated name of the given length.

<ul>

 <li>Every time the application is run, it should generate 10 unique new brand names. Therefore, your main() method will call the generateName() method 10 times, printing the result each time. Your list should be numbered (see example below).</li>

 <li>Turn in only your source files.</li>

 <li>Do not use a package.</li>

 <li>When the requirements refer to odd positions (e.g. 1, 3, 5), this is the position as a business user sees it. <em>We</em> know that the first position is <em>really</em> numbered 0. Careful with this distinction.</li>

 <li>Want to read more about this? https://www.chicagotribune.com/business/ct-confusingdrug-names-0323-biz-20150320-story.html</li>

</ul>

<ol start="3">

 <li><strong>Required Main Class: </strong></li>

</ol>

BrandName

<ol start="4">

 <li><strong>Required Input: </strong></li>

</ol>

None

<strong>             </strong>

<ol start="5">

 <li><strong>Required Output: </strong></li>

</ol>

Your output should look something like the following example; your brand names will be different. It must include your name.

Brand Name Generator – E. Eckert




<ul>

 <li>Sogefakipa</li>

 <li>Sokilupi</li>

 <li>Tikezefabe</li>

 <li>Dikubimanu</li>

 <li>Gizumuxox</li>

 <li>Meviwive</li>

 <li>Xunacum</li>

 <li>Palusoxoro</li>

 <li>Bekajo</li>

 <li>Guvowi</li>

</ul>


