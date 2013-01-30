	var Util = function() {
		HideTableSeparator : function(table) {
			if (Ti.Platform.osname == 'android') {
				var autil = require('org.cathand.autil');
				autil.hideTableRowSepartor(table);
			}
		},
		HideTableFadingEdge : function(table) {
			if (Ti.Platform.osname == 'android') {
				var autil = require('org.cathand.autil');
				autil.hideTableVerticalFadingEdge(table);
			}
		},
		HideScrollFadingEdgeVertical : function(scrollView) {
			if (Ti.Platform.osname == 'android') {
				var autil = require('org.cathand.autil');
				autil.hideScrollVerticalFadingEdge(scrollView);
			}
		},
		HideScrollFadingEdgeHorizontal : function(scrollView) {
			if (Ti.Platform.osname == 'android') {
				var autil = require('org.cathand.autil');
				autil.hideScrollHorizontalFadingEdge(scrollView);
			}
		},
	};
	