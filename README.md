# Leap Training

## Logging in

### Getting to the right site

Let's get started in Polaris Leap by getting to the right site and logging in. First, visit the appropriate link below:

- Leap: https://catalog.richlandlibrary.com/LeapWebApp/login
- Leap Training: https://rlcloud.richlandlibrary.com/LeapWebApp/lo

### Log in with your credentials

Next, login with your credentials:

- First type in:
  - **oz\\**
- Next, enter the first part of your library email:
  - **cwright**
- Your login should look like this:
  - **oz\\cwright**
- Enter the password to your library email

### Select the **Branch** and **Workstation**

#### Branch

Choose between either:
- **St. Andrews Indoors**
- **St. Andrews Pick-up Window**

#### Workstation

If you're using a library computer, the correct workstation should automatically be selected. If you're on your personal computer, you'll have a big list to choose from, choose the one that says:

- **Polaris PIP Workstation - SA**

## Workform history

If you click the "hamburger" menu at the top-left portion of the screen, a list of currently open and recently opened workforms (bibliographic record, item record, patron record, record set, etc.) will show up. You can pin this to the side if you'd like.

## Checking items in

On the main screen in Leap will be a **CHECK IN** button (in the library-blue color). Click this and a **Check In** screen will show up, just check in your books here as you normally would.

### Printing a hold slip

If you check in an item that has a hold on it, Leap will ask if you want to print it. Confirm that you would like to print it and a print dialog will appear. To make sure it prints correctly, make sure to **select the reciept printer** and uncheck **Headers and footers** in the dialog.

## Patron registration

Next to the **CHECK IN** button is a **👤➕ NEW PATRON** button. Click that and a Patron Registration form will appear. Just fill in the appropriate information to create the new patron record.

## Searching

### Search Box

If you have a patron's barcode or an item's barcode, you can type it straight into the search box at the top of the screen and Leap will take you to the appropriate workform immediately. Additionally, you can enter keywords into the search box, in which case Leap will show suggested patrons and bibliographic records in the dropdown menu. You can click on any of these to go to their corresponding workform.

### Find Tool

If you click on the Find button to the right of the search box, a dialog box will show up. There are a lot of different ways to use the search, I'll go over some common uses.

Above the search bar in the dialog box will be four options, for example:

> Bibliographic Record -> Basic Search -> All keyword fields -> Keyword (All) ->
> (First)              -> (Second)     -> (Third)            -> (Fourth)

You can change each of these to narrow your searches down. Let's look at some of the options available to you.

***Keep in mind that the third and fourth elements may be different depending on the previously selected search option.***

#### First

When you click on the text for the first option, in my case *Bibliographic Record*, a dropdown list will appear with a lot of options. Some that you might commonly use are:

##### **Bibliographic Record**

This searches for items in the library system such as books, movies, etc. You can sort the returned search list by *Title*, *Author*, and more

##### **Item Record**

This is similar to the Bibliographic Record search, however, there are different ways to sort this list, such as *Assigned Branch*, *Status*, and *Barcode*

##### **Patron**

##### **Record Set**

#### Second

This option always remains the same:

##### **Basic Search**

You'll probably use this option the most, it searches by keywords filtered by the third and fourth options you have selected

##### **Power Search**

This search is a bit confusing at first but can be very useful for quickly searching for specific items using bespoke search terms. Some terms include:

| Mnemonic | Description | Example |
| --- | --- | --- |
| `AB` | Assigned branch | `AB=SA` |
| `AU` | Author | `AU="Tolkien, J.R.R.` |
| `BC` | Barcode | `BC=30080042380127` |
| `CS` | Circulation status | `CS=in`/`CS=out` |
| `GENRE` | Genre | `Genre=Fantasy` |
| `KW` | All keyword fields | `KW="hobbits"` |
| `LA` | Language | `LA=Spanish` |
| `MAT` | Material type | `MAT="DVD"`/`MAT="Blu-Ray"` |
| `PD` | Publication date | `PD=1994` |
| `SU` | Subject | `SU="Libraries"` |
| `TI` | Title | `TI="The Silmarillion` |

The thing that makes the Power Search option so... powerful is that you can combine these terms together to quickly find items. The terms you can use when combining the search items are: `AND`, `OR`, and `NOT`. Here's some examples:

- `AB=SA AND AU="Tolkien, J.R.R" NOT MAT="DVD"`
- `GENRE=Mystery OR GENRE=Thriller AND SU=Libraries`
- `KW="ASVAB study guide AND AB=SA`

##### **SQL Search**

This search option isn't commonly used unless you have some experience in SQL.

#### Third

The options available in here will be different depending on the previous options you've selected. Let's assume you've set the first option to **Item Record** and the second option to **Basic Search**. The options will be similar to the Power Search table, just without using any keywords.

#### Fourth

Still assuming **Item Record** and **Basic Search** are the first two options, let's look at what options are available to us if **All keyword fields** is set for the third option:

| Option | Usage |
| --- | --- |
| Keyword (All) | Searches for all the entered words in no order |
| Keyword (Any) | Searches for any of the entered words |
| Phrase | Searches for the exact sequence of entered words in the exact order |

Let's say option three is set to **Title**, the options available to us in the fourth option will now be:

| Option | Usage |
| --- | --- |
| Exact | Searches for the exact sequence of entered words, including punctuation and spacing |
| Exact (*) | Searches for the exact sequence of entered words, but allows additional characters or words before or after the search term |
| Keyword (All) | Searches for all the entered words in no order |
| Keyword (Any) | Searches for any of the entered words |
| Phrase | Searches for the exact sequence of entered words in the exact order |

---

Next, you'll notice a series of icons on the right side of the search box. Let's look at what they do:

| Icon | Usage |
| --- | --- |
| ✕ (X icon) | Clears the search box |
| ★ (star icon) | Saves your settings as your default search settings |
| ᗊ (filter icon) | Brings up another dialog box to add search filters |
| (shopping bag icon) | Brings up another dialog box to set the Record Set options |

The ᗊ (filter) option allows you to basically do a power search in a more visual way.

## Patron Records

Let's say you've searched for a patron's record and opened it. A workform will appear showing their name, card number, and a few buttons: **👤 REGISTRATION**, **ACTIONS ↓**, **⟳**, and **CLOSE**. The registration button will allow you to adjust the patron's settings, actions will let you add to a record set, the ⟳ icon refreshes the record, and close will close the patron's workform, taking you back to the main screen.

Additionally you can go to the different options: **Check Out**, **Out/Overdue**, **Account**, and **Claims/Lost**.

You'll commonly use the default **Check Out** option, just scan the items the patron is checking out and press **COMPLETE** to print a check-out reciept for the patron. 

## Bibliographic Records

Let's say you've opened a workform for a bibliographic item record. There will be a few options you can select from: **SAVE** will be clickable if you adjusted the record, **ACTIONS ↓** will show a dropdown list where you can place a hold, create an item, copy or delete the record, and add to record sets. **LINKS ↓** will let you view the holds queue or the PAC view. The button with an arrow pointing in a window will close the item record and take you back to your search results and close will close the record and either take you to your last-opened workform or the main menu.

At the bottom, you can look at the **⨁︎ Preview** will show the PAC view, the **Items** button will show you each item in our system for that item, the **Record Sets** button will show all associated record sets including the item, the others are self-explanatory.

## Record Sets

Considering you've searched for and opened a Bibliographic Record Set and you have the proper permissions to view/edit it, you'll be able to change general information like the name and add/remove items to/from this record set. Additionally, in the actions button, you can use some of the options available therein.

## Getting more help

On the right-hand side of the screen at the top, click **Help** and a dropdown menu will appear. Select from:

### Leap Topics

When you click this, a new tab will open with documentation on using Leap. This is very useful if you want to go through it to understand things better.

### Keyboard

This will bring up a dialog box with a table of shortcuts and their actions:

#### Actions

| Ctrl + Shift + | shortcut |
| --- | --- |
| New Patron | y |
| Check in | / |
| Filter | f |
| Complete Checkout | . |
| Save | z |

#### Patron Views

| Ctrl + Shift + | shortcut |
| --- | --- |
| Check Out | 1 |
| Out/Overdue | 2 |
| Account | 3 |
| Claims/Lost | 4 |
| Holds/Held | 5 |
| Notes | 6 |
| Reading History | 7 |
| Associations | 8 |
| Notices | 9 |
| Registration | ; |

#### MARC Editor

| Ctrl + | shortcut |
| --- | --- |
| Insert subfield delimiter (‡) | q |
| Insert tag | i |
| Delete tag | d |
| Move focus up | Up arrow |
| Move focus down | Down arrow |
| Display/hide hint | h |
| Open/Close | e |
| Save changes and close | s |

| Shift + | shortcut |
| --- | --- |
| Move tag up | Up arrow |
| Move tag down | Down arrow |

### About

This dialog box will show information about the system as well as your user name, domain, ID, branch, workstation, and computer name.