ISA-Tab Viewer
============

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.11084.svg)](https://doi.org/10.5281/zenodo.11084)

A web viewer for ISA-Tab files hosted as 'gists' on Github or on your own file system. Gone are the days of only using ISAcreator.

### Examples


#### Render from files on your web server

Provided the files are hosted on the same server your page is running on, you can just do this to load in your ISA files!

```
    ISATabViewer.rendering.render_isatab_from_file('test_data_sets/BII-S-3/i_gilbert.txt', '#investigation_file', {});
```

#### Render from a Gist

If you put your ISA files on github as gists, you just need to supply the gist id and call this function.

```
	ISATabViewer.rendering.render_isatab_from_gist('2c606f6be7fc59ff196c', '#investigation_file');
```

And this is the result! 

![image](https://isaagents.files.wordpress.com/2014/06/localhost-63343-sharkkahuna-example-html.png?w=800)

### Demo

[View the demo](https://isa-agents.org/format/examples/). 

# Future Work

Create a super lightweight whole repository viewer just using the ISA files. Searching and filtering will also be available and configurable.

# Developers

The ISA team, at the University of Oxford. Created as part of the ISA-a-thon at the BGI Hong Kong offices in China.

# License

MIT License
