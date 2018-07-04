---
permalink: /
title: "About Me"
excerpt: "Stuff about me!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
```Matlab
% -----------------------------------------------------------------------
% Check for master scripts and get dir
% -----------------------------------------------------------------------

masterscriptdir = fileparts(which('Second_level_analysis_template_scripts/0_begin_here_readme'));

if isempty(masterscriptdir)
    error('Add Second_level_analysis_template_scripts folder from CANlab_help_examples repository to your path'); 
end
```