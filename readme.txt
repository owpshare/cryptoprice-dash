npm install -g polymer-cli # install the command line interface

# install polymer template using bower
# choose polymer-2-element for this project
# results in the following web components: polymer, shadycss, webcomponetsjs
polymer init

bower install --save PolymerElements/iron-ajax
bower install --save PolymerElements/paper-spinner
bower install --save chart.js
bower install --save moment
bower install --save paper-button
bower install --save PolymerElements/paper-styles
bower install --save PolymerElements/iron-flex-layout

polymer serve

Notes:
Lecture 40: response = Event.detail.__data.response.data.amount.
Lecture 47: Event.detail.__data.response.data.