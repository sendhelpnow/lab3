#Change Log

Team membership:  Calvin Lai CL (Captain) & Michaela Yoon MY (Mate)  
Team conventions: Allman notation, markdown for changelog  
Changelog format: [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) 

## [Unreleased]
## [0.0.2] - 2018-01-27
### New Component
- Created new simple model Images.php and _cell.php to handle single images MY

### Updated component
- Removed duplicate template from about.php and gallery.php MY
- config/autoload.php was updated so database driver can be preloaded MY
- Modified template.php, welcome.php, Welcome.php, Gallery.php to finish
  dynamic database driven content MY

## [0.0.1] - 2018-01-25
### New Component
- Made new controllers for About and Gallery MY
- Moved about, gallery, index from public to views and changed from html to php (index renamed to welcome) MY

### Updated component
- Modified template.php, about.php, welcome.php, MY_Controller.php, Welcome.php, Gallery.php, About.php to
    set up for dynamic database driven content CL
- The Welcome controller now points to welcome view MY
- Headers in about, gallery and welcome view now refer to controllers instead of static html MY
