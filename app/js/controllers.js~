'use strict';

/* Controllers */
google.load("visualization", "1", {packages:["corechart"]});
google.setOnLoadCallback(function () {
    angular.bootstrap(document.body, ['myApp']);
});
angular.module('myApp.controllers', []).
  controller('MyCtrl1', ['$scope',function($scope) {
	var data = google.visualization.arrayToDataTable([
          ['Year', 'Sales', 'Expenses'],
          ['2004',  1000,      400],
          ['2005',  1170,      460],
          ['2006',  660,       1120],
          ['2007',  1030,      540]
        ]);
	var options = {
          title: 'Company Performance'
        };
        var chart = new google.visualization.LineChart(document.getElementById('chartdiv'));
        chart.draw(data, options);
  }])
  .controller('MyCtrl2', [function() {

  }]);

