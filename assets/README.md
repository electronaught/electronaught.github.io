# How to add assets to your blog posts

To add and access supplemental blogpost material:

1. Create and name a folder for your specific post (Ex: EN116, as seen here)
1. Place any post-specific materials inside so you can keep things tidy

In your posts, you can then access this material by indexing into this folder and referencing individual files by name.  For example:

`![<Material Description>](/assets/EN116/test_pic.png)`

This will display `test_pic.png` with the material in the EN116 markdown file.  

To center images, simply wrap the statement with some in-line CSS:

```
{:refdef: style="text-align: center;"}
![Preferred Circuits Collection](/assets/EN116/test_pic.png)
{: refdef}
```