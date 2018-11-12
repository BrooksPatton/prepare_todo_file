# prepare_todo_file
Process an inbox and prepare the todo-app.json file for usage

## Description

This command line application will help me prepare my todo app for getting things done.

The idea is that during the day I will add things to my inbox via a web app.

Then I will run this command line app that will process those tasks. It will also ask for any other tasks (like mail or calendar items to add to the list)

Then it will look through the completed items and re-add any repeating tasks to the list.

Finally it will sort the items so that when I do things I don't have to search to find out which one to work on.

## User Stories

* [ ] As a doer, I want to process every item in the inbox
  * [ ] Loop through each inbox item and gather the following data
    * [ ] task name
    * [ ] why
    * [ ] category
    * [ ] deadline
    * [ ] repeating
    * [ ] company or personal
    * [ ] importance
    * [ ] someday / maybe
    * [ ] Note as waiting for
    * [ ] description
    * [ ] delete
* [ ] As a doer, I want to add extra tasks to my todo list
  * [ ] Add one off tasks to the list with the following data
    * [ ] task name
    * [ ] why
    * [ ] category
    * [ ] deadline
    * [ ] repeating
    * [ ] company or personal
    * [ ] importance
    * [ ] someday / maybe
    * [ ] Note as waiting for
    * [ ] description
    * [ ] delete
* [ ] As a doer, I want to add repeating items to my todo list
  * [ ] Re-add to do items that were completed and it is their time to be re-added
* [ ] As a doer, I want my todo list to be sorted so that I don't have to think about what to do next
  * [ ] Deadline with high importance
  * [ ] sorted by category that is most below working threshold
  * [ ] sorted by most important to least
* [ ] As a doer, I want to be able to add an emergency item to the top of the list
  * [ ] interactively
  * [ ] directly from the cli
