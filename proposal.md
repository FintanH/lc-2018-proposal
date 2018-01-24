**Abstract Title**: Read The Functional Manual: But First We Need to Write It

**Abstract Topic**: Documentation Writing, Community Interaction, Open Source Contributions

**Submission Type**: Educational Session (50m)

**Abstract Summary**: 

## Intro
People who work with software libraries, whether in-house or open source, rely on the documentation of these libraries. The original author(s) were able to express the functionality of this library via code but this does not necesarrily mean that a new onlooker can use it immediately. This is where documentation, tutorials and blog posts come in.

Being in the Haskell community, a common complaint that is often heard is that the documentation for libraries can range from poor to non-existent. This does not mean that _all_ libraries have poor documentation. In fact there are a few that have excellent resources and are written about a lot. What we will dicuss in this talk is the way we, as a community, can improve the poor documentation and dispell this complaint from our community.

## Levels of documentation
We will discuss in this section the levels of documentation that you will come across and how each one helps with a newcomers understanding to a library.

### Types as documentation
Types can serve as documentation but only at opportune moments. They should not serve as documentation completely! This type of documentation will come in the form of well named types and also function naming. We can infer a lot about what is going on with proper type and function names.

### Documenting Functions
After useful type names, the next thing a user will look for is documentation for that specific function. This should at least have a one sentence description of what the function does. If the function is more involved then there should be more description given and, for bonus points, small examples of use.

### Example Usage
This is the next step in evolution for a library. Once there is a collection of functions that make up the library there is meaningful ways you can combine them. An example usage section showcases these combinations. It should take the user of the library from getting started, building up on more complicated examples as we progress. This can be complemented by having runnable examples.

### The Code Lab
The code lab is very similar to example usage. What differs is that there is a clear continutation of the examples as the concepts build upon each other. The code lab's goal is to make the user really understand the motivations of the library and how to use it. It will even prompt the reader to take part in exercises to concretise the knowledge they are gaining while reading.

### Blog Posts
Blog posts serve as an outside source for a library or set of libraries. They serve as a stream of conciousness of someone using the library, usually in more concrete settings. Blog posts can come in the form of example usage, where the post's author seeks to convey more information about the library in their use case. They can also appear in the form of a code lab, where the author has gained insight into the library and now want to reconvey this information to other users; a great example of this is the Lenses Over Tea series.

## Call For Participation
Now that we have covered the different ways of documenting libraries, here is the crux. A call to action to you, the Haskell community. As we use libraries and come across libraries that are not sufficiently documented it should be a part of our duty to record how we use these libraries. In turn we should turn this into documentation for the library. The authors of these libraries will be ever thankful. They have put in a lot of work to get the library this far and it is not always easy to find time to expand on this further. I implore you to contribute even if it is as small as a typo fix or fixing an example. Then as you become more comfortable this will expand into more open source contributions. You will become more familiar with the libraries you contribute to via documentation and can then expand on further development.

**Content Relevancy**: Useful for everybody.
