//tol
	if ((newkeys & KEY_CROUCH)&& GetPlayerState(playerid) == PLAYER_STATE_DRIVER)
    {
        	if(IsPlayerInRangeOfPoint(playerid,12.0,35.581932067871, -1539.7443847656, 4.9923849105835))
         	{
         		RotateObject(tol1, 1, 0, 89, 20, 11.5);
           		SetTimer("closetol1",4000,0);
	            GameTextForPlayer(playerid, "~r~-$5", 5000, 1);
	            GivePlayerCash(playerid, -5);
	            SendClientMessageEx(playerid, COLOR_WHITE, "Palang telah dibuka dan akan menutup dalam waktu 4 detik ");
           	}
            if(IsPlayerInRangeOfPoint(playerid,12.0,67.376449584961, -1524.0074462891, 4.7072782516479))
            {
	            RotateObject(tol2, 1, 358, 89, 20, 11.5);
	            SetTimer("closetol2",4000,0);
	            GameTextForPlayer(playerid, "~r~-$5", 5000, 1);
	            GivePlayerCash(playerid, -5);
	            SendClientMessageEx(playerid, COLOR_WHITE, "Palang telah dibuka dan akan menutup dalam waktu 4 detik ");
            }
            if(IsPlayerInRangeOfPoint(playerid,12.0,-80.364051818848, -887.17596435547, 15.519337654114))
         	{
	            RotateObject(tol3, 359.89562988281, 0.84765625, 333.55590820313, 20, 11.5);
	            SetTimer("closetol3",4000,0);
	            GameTextForPlayer(playerid, "~r~-$5", 5000, 1);
	            GivePlayerCash(playerid, -5);
	            SendClientMessageEx(playerid, COLOR_WHITE, "Palang telah dibuka dan akan menutup dalam waktu 4 detik ");
            }
         	if(IsPlayerInRangeOfPoint(playerid,12.0,-87.734375, -933.43475341797, 19.411485671997))
          	{
	            RotateObject(tol4, 358.2421875, 358.62023925781, 333.34716796875, 20, 11.5);
	            SetTimer("closetol4",4000,0);
	            GameTextForPlayer(playerid, "~r~-$5", 5000, 1);
	            GivePlayerCash(playerid, -5);
	            SendClientMessageEx(playerid, COLOR_WHITE, "Palang telah dibuka dan akan menutup dalam waktu 4 detik ");
            }
	        if(IsPlayerInRangeOfPoint(playerid,12.0,1735.7113037109, 559.13702392578, 25.582683563232))
            {
	            RotateObject(tollv1, 0, 0, 342, 20, 11.5);
	            SetTimer("closetollv1",4000,0);
	            GameTextForPlayer(playerid, "~r~-$5", 5000, 1);
	            GivePlayerCash(playerid, -5);
	            SendClientMessageEx(playerid, COLOR_WHITE, "Palang telah dibuka dan akan menutup dalam waktu 4 detik ");
            }
			if(IsPlayerInRangeOfPoint(playerid,12.0,1747.2774658203, 502.59899902344, 28.599391937256))
            {
	            RotateObject(tollv2, 0, 360, 341, 20, 11.5);
	            SetTimer("closetollv2",4000,0);
	            GameTextForPlayer(playerid, "~r~-$5", 5000, 1);
	            GivePlayerCash(playerid, -5);
	            SendClientMessageEx(playerid, COLOR_WHITE, "Palang telah dibuka dan akan menutup dalam waktu 4 detik ");
            }
