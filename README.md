# Energy communities:
This project aims to collect data on energy communities from Germany, Denmark, and the Netherlands, then estimate the treatment effect associated with selected policy interventions in these countries.

By initiating searches in the national firm registries of the countries, putting search words connected to energy and specifying the legal form of the firm (cooperative, limited partnership, association) the date of founding and the name of the firm is collected, along with the legal form, country, and the type of energy they produce. The goal is to build a dataset mapping out these energy communities in the three countries specified. 

The German dataset is composed of cooperatives and limited partnerships in the energy industry found on the German firm registry website:  https://www.unternehmensregister.de/ureg/registerPortal.html;jsessionid=5E900DEAFF9D2FB43B6DBDAC53C058F8.web04-1
The code is provided for cooperatives in Germany. For collecting data on limited partnerships, the same code was run with the search modified from cooperatives to limited partnerships. 

Data on energy communities in Denmark was downloaded manually from https://businessindenmark.virk.dk/. 

For the Netherlands, data was collected from the Bedrijvenmonitor  https://bedrijvenmonitor.info/branche/bedrijven-in-de-branche-energie-productie-en-distributie?page=1 and the inventory of the Lokale Energie Monitor on Dutch energy communities: https://www.hier.nu/lokale-energie-monitor-2022#bijlagen-downloads 

For Germany, the following search words were used to find companies in the energy industry: Energie, Bürgerenergie, Energiegenossenschaft, Wasserkraft, Windkraft, Elektrizitätsversorgung, Energieversorgung, Strom, Solarstrom, Sonnenstrom, Kraftwerk, Windenergie, Windpark, Solarpark, PV, Photovoltaik, Wasserkraft
On the Danish websites, the energy industry could be selected as a filter in the search, hence, these search words were not needed. 

According to regulations for energy communities in each country, the following legal forms were considered: 
    Germany: Limited liability companies and cooperatives
    Denmark: Cooperatives and partnership (where under ownership this is written: The real owner cannot be identified or found,
the board is used as the real owner ("Reel ejer kan ikke identificeres eller findes ikke, ledelsen
indsat som reel ejer")
    Netherlands: Cooperatives and associations. 


