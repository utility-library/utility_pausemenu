# GetCurrentPauseMenu
Return the current pause menu that is being displayed.

??? success "Returns"
    | Data Type                            | Description
    | ------------------------------------ |-------------
    | string | "map", "settings", "pause"

---
??? example
    ```
    local menu = exports["utility_weapons"]:GetCurrentPauseMenu()
    ```