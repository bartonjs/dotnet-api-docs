all: ChannelServices_GetChannel_Share.dll channelservices_getchannel_client.exe 

ChannelServices_GetChannel_Share.dll: ChannelServices_GetChannel_Share.cs
	csc /t:library ChannelServices_GetChannel_Share.cs

channelservices_getchannel_client.exe : channelservices_getchannel_client.cpp ChannelServices_GetChannel_Share.dll
	cl /clr channelservices_getchannel_client.cpp