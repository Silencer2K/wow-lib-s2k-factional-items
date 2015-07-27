LibS2kFactionalItems
====================

A library to convert ItemId to ItemId of player's faction.

Synopsis:
---------
    local S2KFI = LibStub("LibS2kFactionalItems-1.0")

    itemId = S2KFI::GetConvertedItemId(itemId, 'alliance') or itemId  -- convert to alliance
    itemId = S2KFI::GetConvertedItemId(itemId, 'horde') or itemId     -- convert to horde
    itemId = S2KFI::GetConvertedItemId(itemId) or itemId              -- convert to players' faction
