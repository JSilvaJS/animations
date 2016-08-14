# Synopsis
Learning the basics of CSS transitions and using calc to create movement on a page. 

# Sample Code
``` CSS
.slid {
	left: calc(100% - 200px);
}

button {
	background: blue;
	color: white;
	padding: 10px;
	border: 1px solid white;
	transition: all 3s ease .5s;
	&:hover {
		background: green;
		padding: 20px;
	}
}
```
