# Web
This is an attempt to update the Academic Theme. 
It is non compatible with my version.

This is a submodule within the dddiaz.com repository.  
Originally forked from the Academic repo.

# How to checkout
#### TODO: add this to build
git submodule add https://github.com/dddiaz/academic-kickstart web
git submodule update --init --recursive

# First Time Setup:
- Update web/config/_default/params.toml to control top level config.
- content/home/ to turn off and on widgets
    - customize position with weight
- update config.toml with website title
    
    
# TODO:
- Update google analytics config in params.toml
- update build to update submodules
- update base url in config.toml
- update web icon
- add resume pdf to content/authors/admin/index
