# corrupted_document_challange

<b> Problem context</b><br>
An English document has been corrupted in an unusual manner. Each alphabetic word (no numbers, but
apostrophes allowed) has had every other character replaced with a # character. For example, a sentence like
I'm here. It's a cat.<br>
would appear in the document as<br>
I#m h#r#. I#'# a c#t.<br>
We have extracted the tokens from this corrupted document and have provided the list of tokens to you as
corrupted_tokens.txt. Note that the order of tokens in the list is the same as how they appeared in the
original document, and that surrounding punctuation like . and , have been removed.<br>
As an example, if the uncorrupted document is:<br>
I'm here. It's a cat.<br>
the its corresponding corruption followed by tokenization would be:<br>
I#m<br>
h#r#<br>
I#'#<br>
a<br>
c#t<br>
