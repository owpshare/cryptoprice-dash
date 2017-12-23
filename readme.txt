npm install -g polymer-cli # install the command line interface

# install polymer template using bower
# choose polymer-2-element for this project
# results in the following web components: polymer, shadycss, webcomponetsjs
polymer init

bower install --save PolymerElements/iron-ajax
bower install --save PolymerElements/paper-spinner

polymer serve

Notes:
Lecture 40: response = Event.detail.__data.response.data.amount.