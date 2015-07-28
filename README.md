LibS2kFactionalItems
====================

A library to convert ItemId to ItemId of player's faction.

Synopsis:
---------
    local S2KFI = LibStub("LibS2kFactionalItems-1.0")

    -- convert to alliance
    itemId = S2KFI::GetFactionalItemId(itemId, 'alliance') or itemId

    -- convert to horde
    itemId = S2KFI::GetFactionalItemId(itemId, 'horde') or itemId

    -- convert to player's faction
    itemId = S2KFI::GetFactionalItemId(itemId) or itemId
