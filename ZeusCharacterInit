_unit = _this;

_bodyParts = ["head","body","hand_l","hand_r","leg_l","leg_r"];
_woundTypes = ["backblast", "bite", "bullet", "explosive", "falling", "grenade", "punch", "ropeburn", "shell", "stab", "unknown", "vehiclecrash"];

_woundCount = random 8;

for "_i" from 1 to _woundCount do 
{
	_severity = random [0.4, 0.7, 0.9];
	
	_part = selectRandom _bodyParts; 
	_woundType = selectRandom _woundTypes; 
	
	[_unit, _severity, _part, _woundType] call ace_medical_fnc_addDamageToUnit; 
	
	systemChat format ["Dealt %1 wound to %2 Severity: %3", _woundType, _part, _severity];
};
