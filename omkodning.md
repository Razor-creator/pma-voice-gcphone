# Omkodning

Nedenfor vil jeg lave et dokument hvor mna kan se hvad tilsvarende er når man bruger andre systemer end pma men gerne vil skifte over til det.

# Guide Til Telefon

Set Call Channel:

PMA-Voice:
exports['pma-voice']:setCallChannel(callet) -- Callet kan ex være: infoCall.id+1 eller 0 for ikke at fjerne fra

Mumble-Voip:
exports["mumble-voip"]:SetCallChannel(callet) -- Callet kan ex være: infoCall.id+1 eller 0 for ikke at fjerne fra

Toko-Voip:
exports.tokovoip_script:addPlayerToRadio(callet) -- Callet kan ex være: infoCall.id+1 eller 0 for ikke at fjerne fra


Remove player from radio:

PMA-Voice:
exports['pma-voice']:removePlayerFromRadio() -- Her behøves intet i parantesen da den bare fjerner dig fra alt.

Toko-Voip:
exports.tokovoip_script:removePlayerFromRadio(TokoVoipID) --Har skal du bruge TokoVoipID'et i parantesen.


OBS: Der bliver løbende tilføjet mere til denne fil





