# Our Map

Tracking system for Our Book

## Serial Numbers

Each book is uniquely identified by a serial number.
Each serial number is a set of fields separated by periods.

### Example

    BD.01-02-14.DUNCANIFORGOT.0873
    ^  ^        ^             ^
    |  |        |             |
    |  |        |             | Book number 0873
    |  |        |
    |  |        | Book made by OMGDUNCANIFORGOT
    |  |
    |  | Book made on February 1, 2014
    |
    | Book version is Declaration of Human Rights

### Fields

The fields may be written in any order, so long as each field obeys these format rules and examples:

- #### Book Version

  #### `B<letters or digits>`

    - `BD` for a Declaration of Human Rights version
    - `BIF` for a Rudyard Kipling's If version
    - `BP` for a *DUNCAN I FORGOT WHAT THIS IS*
    - `BQ` for a *DUNCAN I DON'T REMEMBER THIS EITHER*

- #### Book's Date of Creation

  #### `<2 digits for day>-<2 digits for month>-<4 digits for year>`

    - `31-12-2014` for December 31, 2014

- #### Book Maker ID

  #### `<some digits><some letters>`

    - `1DI` for *DUNCAN WHAT IS THIS I DON'T EVEN*
    - `2XX` for *DUNCAN WHAT IS THIS I DON'T EVEN*
    - `3XX` for *DUNCAN WHAT IS THIS I DON'T EVEN*
    - `4XX` for *DUNCAN WHAT IS THIS I DON'T EVEN*

- #### Book Number

  #### `<some digits>`

    - `456` for book number 456 *DUNCAN WILL THERE EVER BE DUPLICATES OF THIS NUMBER HOW DOES THIS WORK IS THIS NUMBER 456 OF THAT VERSION OR THAT MAKER OR OF ALL TIME OMG HELP*
    

