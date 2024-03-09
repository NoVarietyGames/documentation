# purchaseSuccess

This event fires when a purchase dialog for a [pass](https://create.roblox.com/docs/production/monetization/game-passes) is closed. It fires as the dialog closes, when the player presses "Cancel" at the prompt or "OK" at the success/error message.

<pre class="language-lua"><code class="lang-lua"><strong>marketplace.purchaseSuccess(callbackFunction: function): void
</strong>
marketplace.purchaseSuccess(function(<a data-footnote-ref href="#user-content-fn-1">player: PlayerObject</a>, purchaseType: Enum, wasPurchase: Boolean)
    -- Enum.PurcahseType GamePass | MemberShip | Product
    -- wasPurchase only returns for GamePasses and Product not MemeberShip
    if purcahseType == Enum.PurcahseType.GamePass then
        print(player.Name .. " purchased a gamepass")
    elseif purcahseType == Enum.PurcahseType.Product then
        print(player.Name .. " purchased a product")
    else
        print(player.Name .. " purchased a membership")
    end

end)
</code></pre>

[^1]: [player.md](../player.md "mention")
