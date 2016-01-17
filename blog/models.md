			In our blog 

			Features
			==============
			Blog will have the following features

			1. Post(Table in database)
			2. Categories(Table in database)
			3. Tag(Table in database)
			4. Author(Table in database)

			Let us make a relation between our tables
			================
			1. Post can have many categories, and a category can have many posts(Relation between post and category table)(ManytoMany relation)

			2. a tag can have many post a post can have many tags(ManytoMany relation)

			3. author can have many posts and a post can have a single author(OneToMany relation) [a post cannot be written by more than one author]

			Attributes for tables
			======================
			Post
			=======
			1. title
			2. created_date
			3. body
			4. tags
			5. cathegories
			6. author

			Categories
			========
			1. name
			2. description

			Author
			=========
			1. Author name
			2. Author e-mail (not mandatory)
			3. Author bio

			Tag
			=========
			1. tag_name