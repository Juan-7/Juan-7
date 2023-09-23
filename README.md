stock Clearchat(playerid, lines)
{	
	for(new i = 0; i < lines; i++)
	{	
		SendClientMessage(playerid, 0xFFFFFFFF, "");
	}
	return 1;
}

MODO DE USO:
OnPlayerConnect(playerid)
{
  ClearChat(playerid, 20); //20 è a quantia de vezes que ele ira flodar no chat apos se conectar!
  return 1;
}
