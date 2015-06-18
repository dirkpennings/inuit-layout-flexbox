# inuit-flexbox

A flexbox grid system for [inuitcss framework](http://www.inuitcss.com).

## Work in progress

This is a work in progress. Use it at your own risk !

## Manual

### Gride type

The default grid use flexible column width.  
But by setting `$inuit-flexbox-fixed-grid-enable: true;`, the column width will
be fixed like in a classical grid system. The fixed grid system is based on
12 columns.

### Code

    <div class="flex">
        <div class="flex__item
                    flex__item--full
                    flex__item--lap-and-up--1
                    flex__item--desk--1">
        </div>
        <div class="flex__item
                    flex__item--1
                    flex__item--lap-and-up--2
                    flex__item--desk--4">
        </div>
        <div class="flex__item
                    flex__item--1
                    flex__item--lap-and-up--1
                    flex__item--desk--2">
        </div>
    </div>
