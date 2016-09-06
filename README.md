This repo contains information and files related to my GitHub Challenge from 8/23/16 - 9/23/16.
I intend to:
1.  Complete the code school course "Try Ruby"
2.  Complete the following code school course in the Ruby Path
3.  If I feel ready, I will build a simple app using Ruby. Otherwise, I will complete another code School course or seek other resources and tutorials
4.  I will research and attempt to rebuild a previous basic app/assignment using new technology.  



~~~~~~~~~~~~~~~~
-- 8/25/16       Working through the "try ruby" course on code school 8/25/16
So far, the methods in Ruby seem very similar to Javascript.  I like the "to_s" to stringify method (for example).

Other methods on strings, arrays, objects, etc:  
poem.lines.to_a.reverse.join   

~~~~~~~~~~~~~~~
-- 8/26/16
Instead of "objects" (like in JavaScript), Ruby uses "hashes".
Hashes have  key/value pairs.  
If you want to see the list of the keys in a hash, just do hashname.keys
To build a new empty hash:  

     newhashname = Hash.new(0)
      {}

books.values.each { |rate| ratings[rate] + = 1}
above is a command that takes all the unique values in the hash "books" and turn them into keys..  as ratings.  It is also giving a command to increment the number of ratings per key (each unique value in "books")...
~~~~~~~~~~~~~~~~~

--8/27/16
So far, I'm getting introduced to certain syntax and commands that exist within Ruby.  I haven't researched thoroughly enough to be able to explain what Ruby IS..  But so far, I think it is a language that takes the place of JavaScript.  
This lesson has introduced some commands that have to do with directories..  So this is interesting to me because I'm wondering how/when we will be referencing directories within applications in Ruby.  I suppose we do that any time we are referring to a path and specific file within a directory in JS. I am wondering if Ruby has its own "built in command line" feature..
I will find out!
There are some really great methods I am seeing here!!  Ruby SEEMS like it contains straightforward commands to create html code in a blend of JS-like code.  Just learned a method that creates a popup with directives to create headers and p tags (using Ruby syntax) in order to make a list of items on the DOM (I think it's on the DOM).

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

--8/28/16
I finished the Try Ruby introduction to syntax tutorial yesterday. Today, I completed the first two levels of the course 'Rails for Zombies' at CodeSchool.  Now it is becoming apparent that Ruby is the database part of a full stack application which is written in the Rails language?  That is still to be researched and learned.
I am LOVING working with different types of databases.  So far, I really enjoyed problem solving in the MEAN stack with MongoDB and Mongoose, as well as using a SQL DB and PostgreSQL.  Now, Ruby is awesome.  It is very intuitive after working with other types of databases.  The methods are straightforward.  CRUD (Create, Read, Update, Delete) with Ruby is great.  There is a    TableName.create method  (or Table.new and .save), there is a TableName.find(#) with an id value, there is a TableName.update method or find, set new values and save.  The delete method is actually TableName.destroy.  So far so good.  I made it through two levels today.  Good work for a Sunday.  

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

-- 8/29/16 --> 9/4/16
I've continued to work my way through 4 levels of the code school course for getting started with Ruby.  
The Syntax is very intuitive and I am liking the embedded commands in the HTML.  
Trying to start a basic Ruby project is proving to be a little less intuitive.  The "gem commands" were not working.  I tried the "sudo gem install rails" command.  Still running into trouble with installation.  So I will continue learning the syntax in the code school challenges!


~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
9/5/16
Continuing with the Rails code course on code school, I am enjoying learning a syntax.  Today's lesson introduced a principle which makes Rails so popular with some people.  Convention over configuration.  It seems Syntax, convention are very important in Rails.  It makes things follow along very intuitively after having learned and worked with JS, Anguar, and SQL/Mongo.  Today I learned a bit about how the controllers work in Rails.  The naming of the files makes the action calls and accessing of info and models very easy.  Or so it seems at this point. 
