    local success = exports['mazebank_door']:StartMazeBankDoor()
    if success then
        ESX.ShowNotification('Udane')
    elseif not success then
        ESX.ShowNotification('Nie Udane')
    end