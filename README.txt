I - Description
I made this plugin for my community Zombie4Ever.eu and was allowed to share it. Also It was a old plugin before that.
This plugin set the Tag clan and the name bot. Also is faking the ping but you have to know that faking ping for bots is against the rules of Valve as far as I remember.
We don't need anymore Gamedata since
PHP Code:
SetClientName(int client, const char[] name)  
was implemented on SM.

II - Cvars
"drapi_active_bots_names" "1"
"drapi_bots_names_clan" "Zombie4Ever.eu"
"drapi_bots_names_min_ping" "35"
"drapi_bots_names_max_ping" "55"
"drapi_bots_names_interval_ping" "3"

III - Configs
"addons/sourcemod/configs/drapi/bots_names.cfg"
"BotNames"
{
	"BotNames"
	{
		"1"		"????ù???? ???"
		"2"		"? ? Pyro-Bro™ ? ?"
		"3"		"?SylexSirius?"
		"4"		"°™Alex™°"
		"5"		"¥-×xXx×-¥-?=SurNuK=-¥-×xXx×-¥"
		"6"		"¡? D2i V[i]sT1ruk2s~?"
		"7"		"«§ÞårrØW»"
		"8"		"°-=Sn[A]ke=-°™"
		"9"		"·?????????®Pppp??"
		"10"	"°??Z€LSiK??°"
		"11"	"»Â?icø™šolë£ÿ«"
		"12"	"»SysSTémek«"
		"13"	"»ss! -nesulike"
		"14"	"Ðr.SviL"
		"15"	"×•·ï¡[?t??$?T]¡ï·•×"
		"16"	"Þÿççk??"
		"17"	"Ð?îve? ™"
		"18"	"Ðevastator"
		"19"	"¬Chocolate¬"
		"20"	"©º°Fight.??e°º©"
	}
}

IV - Changelogs
V1.0.1
-Added cvar "drapi_active_bots_names_ping" to Enable/Disable Bots fake ping.