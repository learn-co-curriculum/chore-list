# Chores List

You'll be making an app to track your chores. This will be similar to the shopping list app we created in class.

![](http://i.giphy.com/xTiTnuhyBF54B852nK.gif)

## Instructions

  1. [Use the Flatiron iOS Template](http://bit.ly/flatiron-ios-template) FROM SCRATCH
  2. Create `Chore` class. Your `Chore` class should have the name (`String`) of the chore and a `dueDate`. What data type you ask should this `dueDate` be? For right now let's keep it as a `String`. The last property will be `timeEstimate` which should be an `Int`. Create an initializer for these properties as well!
  3. Make a few example `Chore` objects in the `viewDidLoad` of your `MasterViewController`. Add them to the `objects` array and display the chore name in each cell.
  4. When you tap on the cell, it should segue way to the `DetailViewController`, where all of the information is visible.

## Stretch

  1. If the due date is equal to `"tomorrow"` have the name be display IN ALL CAPS.
  2. Modify this [this tutorial](http://www.ioscreator.com/tutorials/delete-rows-table-view-ios8-swift) to implement swipe to delete from your tableview.
  3. Drag a plus `UIBarButtonItem` into the `MasterViewController`. BarButtonItmes are in the object navigator on the bottom right where you pull your `UILabels` from.
  4. Connect up an `IBAction` for the `UIBarButtonItem`
  5. Play with [this tutorial](http://sourcefreeze.com/uialertcontroller-ios-8-using-swift/) (scroll to UIAlertController With TextField) so when the user preses the `+` they are presented with a alert to add a new chore

<a href='https://learn.co/lessons/chore-list' data-visibility='hidden'>View this lesson on Learn.co</a>
