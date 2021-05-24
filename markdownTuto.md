# Mark Down Tutorial
### _Italic_ and __Bold__
- To _italicize_, do `_code_`
- To __bold__, do `__code__`

### Header sizes
- Header size can be adjusted by the amount of `#` that precedes it
- `### Header_size3`
- `## Header_size2`

### Link
- Inline link are formmated like this: `[alt_text](link.com)`
- For example: 
	- `[Search for it.](www.google.com)`  
	[Search for it.](www.google.com)
	- `[You're __really, really__ going to want to see this.](www.dailykitten.com)`  
	[You're __really, really__ going to want to see this.](www.dailykitten.com)
	- `#### The Latest News from [the BBC](www.bcc.com/news)`
	#### The Latest News from [the BBC](www.bcc.com/news)

### Images
- Images are similar to inline links but just `!` before it like `![alt_text](image_link)`
- You can also reference it to keyword and link it to that keyword later such as:
	```
	![Black cat][Black]
	![Orange cat][Orange]
	[Black]: https://upload.wikimedia.org/wikipedia/commons/a/a3/81_INF_DIV_SSI.jpg
	[Orange]: http://icons.iconarchive.com/icons/google/noto-emoji-animals-nature/256/22221-cat-icon.png
	```

### Blockquotes
- If you need to call special attention to a quote, or design a pull quote. A blockquote is a sentence or paragraph that's been specially formatted to draw attention to the reader
- To create a block quote, all you have to do is preface a line with the `>`
- For example:
	```
	I read this interesting quote the other day:
	> "Her eyes had called him and his soul had leaped at the call. To live, to err, to fall, to triumph, to recreate life out of life!"
	```

	I read this interesting quote the other day:
	> "Her eyes had called him and his soul had leaped at the call. To live, to err, to fall, to triumph, to recreate life out of life!"

- If your quote spans multiple paragraphs, use `>` for every blank line such as:
	```
	> His words seemed to have struck some deep chord in his own nature. Had he spoken of himself, of himself as he was or wished to be? Stephen watched his face for some moments in silence. A cold sadness was there. He had spoken of himself, of his own loneliness which he feared.
	>
	> —Of whom are you speaking? Stephen asked at length.
	>
	> Cranly did not answer.
	```
	> His words seemed to have struck some deep chord in his own nature. Had he spoken of himself, of himself as he was or wished to be? Stephen watched his face for some moments in silence. A cold sadness was there. He had spoken of himself, of his own loneliness which he feared.
	>
	> —Of whom are you speaking? Stephen asked at length.
	>
	> Cranly did not answer.

- Block quotes can contain other Markdown elements, such as italics, images, or links.

### Lists

- There are two types of lists in the known universe: unordered and ordered

##### Unordered
- To create an unordered list, you'll want to preface each item in the list with an `*` or `-`. Each list item also gets its own line. For example:
	```
	* Milk
	* Eggs
	* Salmon
	* Butter
	```

	* Milk
	* Eggs
	* Salmon
	* Butter

##### Ordered
- An ordered list is prefaced with numbers. For example:
	```
	1. Crack three eggs over a bowl
	2. Pour a gallon of milk into the bowl
	3. Rub the salmon vigorously with butter
	4. Drop the salmon into the egg-milk bowl
	```

	1. Crack three eggs over a bowl
	2. Pour a gallon of milk into the bowl
	3. Rub the salmon vigorously with butter
	4. Drop the salmon into the egg-milk bowl

- You can choose to add italics, bold, or links within lists, for example:
	```
	* Azalea (_Ericaceae Rhododendron_)
	* Chrysanthemum (_Anthemideae Chrysanthemum_)
	* Dahlia (_Coreopsideae Dahlia_)
	```

	* Azalea (_Ericaceae Rhododendron_)
	* Chrysanthemum (_Anthemideae Chrysanthemum_)
	* Dahlia (_Coreopsideae_ ___Dahlia___)

- You might need to make a list with more depth,or to nest one list within another. All you have to do is to taab each asterisk one space more than the preceding item. For example:
	```
	* Calculus
    	* A professor
    	* Has no hair
    	* Often wears green
	* Castafiore
    	* An opera singer
    	* Has white hair
    	* Is possibly mentally unwell
	```
	* Calculus
    	* A professor
    	* Has no hair
    	* Often wears green
	* Castafiore
    	* An opera singer
    	* Has white hair
    	* Is possibly mentally unwell

### Paragraph

   - A soft break is to seperate lines without a big gap. You can accomplish this by inserting two spaces after each new line. This is not possible to see, since spaces are invisible, but it'd look something like this:

	 ```
	 Do I contradict myself?··
	 Very well then I contradict myself,··
	 (I am large, I contain multitudes.)
	 ```

__Without line break:__
```
this line need to be seperated from the next
the next line
```	
this line need to be seperated from the next
the next line	

__With big line:__
```	
this line need to be close to the next one to flow cohesively.
    
this line is too far away from the one above to flow cohesively.
```	
this line need to be close to the next one to flow cohesively.
    
this line is too far away from the one above to flow cohesively.


__With line break:__
```
this sentence need to be close to the next one for cohesiveness.  
this sentence is close from the one above so it flows cohesively.
```
this sentence need to be close to the next one for cohesiveness.  
this sentence is close from the one above so it flows cohesively.

