_uid = getPlayerUID player;
if (_uid == "76561198053995177") then {
	
	_markerPosBox = "tempPosBox"; 	//"tempPosBox"	ist der Marker, wo die Box hin soll
	_ammobox = funkKiste;					//"funkKiste"		ist die Box um die es geht
	
	_stdPosBox = getPos _ammobox;
	_newPosBox = getMarkerPos _markerPosBox;
	_ammoboxAction = player addAction["Toggle Box", {
		_tempPosBox = getPos _ammobox;
		if ( _tempPosBox select 1 == _stdPosBox select 1 ) then{
			_ammobox setPos _newPosBox;
		}else{
			_ammobox setPos _stdPosBox;
		};
	}];

};
