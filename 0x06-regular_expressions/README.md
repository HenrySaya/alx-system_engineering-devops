# 0x06. Regular expression
Reqular expressions is just an expression used regularly like /ah/
Had quite some good time looking at Repetition token `{m,n}` `?` `+` `*`, word boundaries, quantifiers, character class as well as many other interesting facts like **`Some people when confronted with a problem think "I know regex, I'll use regexp" and now they have 2 problems`** and my 2 problems from such an intro to regex left me with more than 2 problems as I was a ~~noob~~ starting or put it in my regex-fu way `(/n0{2}b/)'`
Anyway started cooking as the chef I am and would present my `*spicy*-wins` together with the recipes all in this repo. Enjoy

![super classic joke in the industry](https://intranet.alxswe.com/images/contents/sysadmin/concepts/29/regex_now_2_problems.jpg)

# *Spicy wins* :page_with_curl:

* **0. Simply matching School**
  * [0-simply_match_school.rb](./0-simply_match_school.rb): Regular expression that must match `School`
![spicy-win1](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/ec65557f0da1fbfbff6659413885e4d4822f5b1d.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240507%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240507T193507Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=4dfc2ba35d93f514cada2f76102cbb95d26d48a5b641f61ed497a824b6c66191)

* **1. Repetition Token #0**
  * [1-repetition_token_0.rb](./1-repetition_token_0.rb): ruby script that implement the `{}` token

![spicy-win2](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/e7db3c377d46453588fc84f3a975661d142fee91.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240507%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240507T193507Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=4b15ab5c26e6e5bab29418ffbf0dbf001f25a5630d0dc11f550e1e6d3f3b0c2c)

* **2. Repetition Token #1**
  * [2-repetition_token_1.rb](./2-repetition_token_1.rb): expression to match 0 or 1 occurence of `b` in `test string`

![spicywin3](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/c59ff11db195d5cf17d1790a5141ae2f234786d2.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240507%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240507T193507Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=ff673a2a72ea10bbf3460c0647d201e97acd57818605f771fd51fce924e9c2f8)

<!-- Unfortunately the spicy wins images are not displayed at all -->

* **3. Repetition Token #2**
  * [3-repetition_token_2.rb](./3-repetition_token_2.rb): ruby script regexp that matches 1 or more occurence of `t` in `hbtn` test cases

* **4. Repetition Token #3**
  * [4-repetition_token_3.rb](./4-repetition_token_3.rb): regexp that matches 0 or more occurence of `t`

* **5. Not quite HBTN yet**
  * [5-beginning_and_end.rb](./5-beginning_and_end.rb): regexp is exactly matching a string that starts with `h` ends with `n` and has only one character in between
