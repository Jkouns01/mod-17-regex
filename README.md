<h1> Matching Hex Value </h1>

<p> This is designed to explain the details of how regular expression works. This regular expression is used to match a Hex value. The description below will explain each piece of the regular expression and how it works.
</p>


<h2>Summary </h2>
<h3> `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/` </h3>
<p> Hexadecimal code is a system where any specific color can be described accurately to a computer, ensuring consistency and accuracy in an electronic display. A hexadecimal color value is a 6 digit code with by a # sign. It defines a color that is used in a program. </p>

<h2> Regex Components </h2>

<h3> Anchors </h3>
Anchor: ^ Code Snipet: /^#

<h3> Description: </h3>

<p> Anchors by themselves don't match any regular expression. Rather they assert something about the string (e.g. beginning, end) based on expressions/matching pattern next to the anchor. <br>

Example: ^This istates that the string must begin with This <br>

The ^ is an anchor that the beginning of the string must match the character #. The # is used to distinguish a certain number from a decimal number.

Quantifiers
Quantifier: ?

Snipet: /^#?

Description: ? states a true or false value. Typically, this makes the preceding symbol optional.

Example: This could be used to distinguish between British and American spelling in a string e.g. colour vs color -- the regex would colou?r

Snipet: [a-f0-9]{6} And Snipet: [a-f0-9]{3}

Description:

Quantifier shows how many time the preceding pattern matches. Normally the regex has to match as many occurrences of a particular pattern as possible. If ? was added, the quantifier would become stagnent, causing the regex to match as few occurrences as possible.

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
Hi, my name is Jacob Kouns and to be frank, I don't know what I am doing. I am trying my best to stay in this class but, every class makes it harder and harder to keep going. I soent a lot of time looking into the hexadecimal stuff and I think I have somewhat of an understanding about this topic. 
