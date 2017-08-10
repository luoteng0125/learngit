Git is a version control system.
Git is free software.
Git is free software.

$scope.EntBasicInfoQuery = function() {
		$remote.post("eweb-enterprise.EntBasicInfoQuery.do", {}, function(data) {
			console.log('企业基本信息');
			$scope.EntBasicInfo = data;
			//EntBasicInfo:企业基本信息
			console.log($scope.EntBasicInfo);
		});
	};



Creating a new branch is quick AND simple

Git is a distributed version control system.
Git is free software distributed under the GPL.



