Git is a version control system.
Git is free software.
Git is free software.

$scope.EntBasicInfoQuery = function() {
		$remote.post("eweb-enterprise.EntBasicInfoQuery.do", {}, function(data) {
			console.log('��ҵ������Ϣ');
			$scope.EntBasicInfo = data;
			//EntBasicInfo:��ҵ������Ϣ
			console.log($scope.EntBasicInfo);
		});
	};


Creating a new branch is quick.