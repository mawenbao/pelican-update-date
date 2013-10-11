# Update Date plugin

## Introduction

This is a simple pelican plugin which can
     1) use the value of `update' metadata as update date
     2) use filesystem's mtime value as update date if the `update' metadata is not defined
     3) save a list of articles ordered descending by update date in the global pelican context
 
New variables:
    1) article.updatedate
    2) page.updatedate
    3) context.articles_updatedate

## License
BSD license, see LICENSE.txt for more details.

