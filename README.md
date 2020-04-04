# css best practice

###flued layout

```css
.content-wrap {
	max-width: 800px;
	width: 85%;
	margin: 0 auto;
	padding: 60px 0;
}
```

###Responsive Media Query

```css
/* Responsive
------------------------------------*/
@media screen and (min-width: 750px) {
	header,
	footer {
		text-align: center;
	}
	.project-item img {
		float: left;
		margin-right: 20px;
	}

	.job-item {
		display: grid;
		grid-template-columns: 1fr 2fr;
		column-gap: 20px;
	}
	.contact-list {
		display: flex;
		justify-content: center;
	}
}

@media screen and (max-width: 749px) {
	h1 {
		font-size: 75px;
		line-height: 0.9;
		margin-bottom: 20px;
	}
	h2 {
		line-height: 1;
	}
	.contact-list a {
		padding: 5px;
	}
}
```
