# Google Forms
function onOpen() {
   var ui = SpreadsheetApp.getUi();
   ui.createMenu("Form Menu")
      .addItem("Create Form, "createForm)
      .addToUi();
}
form.setDestination(fomApp.DestinationType.SPREADSHEET, SpreadsheetApp.getActiveSpreadsheet().getId*())

