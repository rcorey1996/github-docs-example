# Writing Good Documentation

## Step 1 - Using Codeblocks


Codeblocks in a markdown make it *very easy* for tech people to **copy, paste, share** code.
A good _Cloud Engineer_ uses code blocks whenever possible.

Because it allows others to copy and past their code to replicate or research issues


- In order to create codeblocks in markdown you need to use three backticks (`)
- Not to be confused with quotation (')
``` ruby
puts "Hello, World!"
```

- When you can you should attempt to apply syntax highlightng to your codeblocks

<img width= "200px" src="https://github.com/rcorey1996/github-docs-example/assets/71137419/0878d9fb-e621-4c3d-9a71-811190d3296a"/>

Good Cloud Engineers use codeblocks for both Core and Errord that appear in the console.

example of an error
```ruby
Trying to access an element of an array that doesn't exist
array = [1, 2, 3]
puts array[5]
```
Here is an example of using a codeblock for an error that appears in bash.

### Step 3 - Use Github Flovored Markdown Task List [<sup>[1]</sup>](#references)
- [ ] Finish Step 1
- [ ] Finish Step 2
- [ ] Finish Step 3
- [ ] Finish Step 4

# Step 4 - Use Emojis (Optional)
GitHub Flavoreed Markdown (GFM) supports emoji shortcodes.
Here are some examples

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud| `:cloud:` | :cloud: |
| Cloud with Lightning| `:cloud_with_lightning:` | 🌩️|

:cloud:

#Step 5 -how to create a table
[<sup>[2]</sup>](#references)
```md
 Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud| `:cloud:` | :cloud: |
```



## References

- [Default (GPT-3.5)] https://chat.openai.com/c/4f6a92f7-7bff-43df-b9cb-98cc17fc47c2
- [GFM Task List] https://github.github.com/gfm/#task-list-items-extension- <sup>[1]</sup>
- [Basic writing and formatting syntax (Github Flavored Markdown)] https://github.github.com/gfm/
- [GFM Emojis CheatSheet] https://github.com/ikatyang/emoji-cheat-sheet
- [GFM Tables (with extension)] https://github.github.com/gfm/#tables-extension-<sup>[2]</sup>
