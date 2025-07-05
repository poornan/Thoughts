# The Boundary Problem

> #### The Boundary Problem <a href="#ember484" id="ember484"></a>
>
> Here's what I mean by the boundary problem. You have a team that's supposed to own the "checkout experience." Sounds like a clean domain, right? But in practice, checkout touches:
>
> * The product catalog (owned by the catalog team)
> * Inventory management (owned by the inventory team)
> * Payment processing (owned by the payments team)
> * User accounts (owned by the identity team)
> * Fraud detection (owned by the security team)
> * Order fulfillment (owned by the logistics team)
>
> Your "checkout team" doesn't own the checkout process. They own the UI for checkout and maybe some business logic. But every meaningful change requires coordinating with five other teams.
>
> [From:](../external-resources/dysfunctional-cross-functional-teams.md)
