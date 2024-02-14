#IC LAB ASSIGNMENT-1


##Initialize the server


<code>
  git clone https://github.com/NITHIN3387/IC_LAB_ASSIGNMENT_1.git
  cd assignment_1
  npm install
</code>



##Run the server


<code>
  npm run dev
</code>



##API's



###API to register a author


####method: POST

####Params
<ul>
  <li>name</li>
  <li>emailId</li>
  <li>password</li>
</ul>


<code>
  https://localhost:4000/auth/register
</code>



###API to login for a author


####method: POST

####Params
<ul>
  <li>emailId</li>
  <li>password</li>
</ul>


<code>
  https://localhost:4000/auth/login
</code>



###API to get all authors


####method: GET

<code>
  https://localhost:4000/auth/author
</code>



###API to upload a blog by author


####method: POST

####Params
<ul>
  <li>blog</li>
</ul>


<code>
  https://localhost:4000/blog/blogs
</code>



###API to get all blogs of authors


####method: GET

<code>
  https://localhost:4000/blog/blogs
</code>



###API to get blogs of authors by author emailId


####method: GET

<code>
  https://localhost:4000/blog/blogs/:emailId
</code>