# Commands
Here is a list of all the commands that can be used.
<br>

* `/vaults`, `/pv`
  To open your Vaults menu (for players)

* `/iv`, `/ivaults`, `/InsaneVaults` 
  To open the Administrative GUI
* `/ivc Settings ChangeIconFee <Fee>`
  To change the fees which needs to be paid while changing the icon of an vault
* `/ivc Settings ChangNameFee <Fee>`
  To change the fees which needs to be paid while changing the name of an vault
* `/ivc Settings ItemDepositFee <Fee>`
  To change the fees which needs to be paid while depositing an item to a vault
* `/ivc Settings ItemWithdrawFee <Fee>`
   To change the fees which needs to be paid while withdrawing an item from a vault
* `/ivc Settings CreateSharedAccessFee <Fee>`
   To change the fees which needs to be paid while creating a new shared access
* `/ivc Settings TransferOwnershipFee <Fee>`
  To change the fees which needs to be paid while transferring the ownership of an vault
* `/ivc Settings RefundFees <True | False>`
  To change if the vault type cost and paid shared access creation costs should get refunded at vault deletion
* `/ivc Settings VaultTypeFees oneTime`
  To set the vault type cost to a oneTime payment
* `/ivc Settings VaultTypeFees PaymentInterval <Duration>`
  To define a payment interval after which the vault type cost have to be paid (Recurring Cost)
* `/ivc Settings PuttingCostsAndFeesOnGovernment <True | False>`
  To change if the costs and fees should be put on the UltraEconomy's Government Account
* `/ivc Settings VaultTypeFees OverdraftAction <FullLock | Delete)`
  To change the action which should be executed if the vault holder can't afford the recurring vault type cost
  
* `/ivc Features CommunityVault Toggle`
  To toggle the entire community vault feature
* `/ivc Features CommunityVault Manage Rename <Name>`
  To customize the shown name of the community vault
* `/ivc Features CommunityVault Manage IgnoreFees <True | False>`
  To toggle if fees should get ignored while interacting with the community vault
* `/ivc Features CommunityVault Manage NewUserArrival NewUserStateDuration <Duration>`
  To define a specific duration how long users are stated as NewUser
* `/ivc Features CommunityVault Manage NewUserArrival WithdrawableItemAmount Unlimited`
  To set the amount of withdrawable items while a user is stated as NewUser to unlimited
* `/ivc Features CommunityVault Manage NewUserArrival WithdrawableItemAmount <Amount>`
  To define a specific amount of items which can each user withdraw while stated as NewUser
* `/ivc Features CommunityVault Manage NewUserArrival Toggle`
  To toggle the NewUserArrival Feature
* `/ivc Features VaultExtendsInventory <True | False)`
  To toggle the VaultExtendsInventory Feature
* `/ivc Features CustomCommandAlias CustomAlias <Alias>`
  To customize the vault quick access command alias
* `/ivc Features CustomCommandAlias Toggle <True | False>`
  To toggle the vault quick access command alias
* `/ivc Features VaultPurgeFeature toggle`
  To toggle the vault purge Feature
* `/ivc Features VaultPurgeFeature ForcePurge`
  To force purge all existing Vaults
* `/ivc Features VaultPurgeFeature PurgeInterval <Duration>`
  To define a specific duration after which all existing vaults are getting purged (Recurring Purge)

* `/ivc Vaults CreateUnpaid <User> <VaultType>`
  To create a vault for specified user without having to pay any costs for the creation
* `/ivc Vaults VaultType list`
  To list all VaultTypes
* `/ivc Vaults VaultType Create <Name>`
  To create a new VaultType
* `/ivc Vaults VaultType Delete <Name>`
  To delete a specific VaultType
* `/ivc Vaults VaultType Manage <VaultType> Name <newName>`
  To rename a VaultType
* `/ivc Vaults VaultType Manage <VaultType> Size <newSize>`
  To redefine the size of an VaultType
* `/ivc Vaults VaultType Manage <VaultType> Permission <newPermission>`
  To optionally set a permission for an VaultType 
* `/ivc Vaults VaultType Manage <VaultType> PurchasePrice <newPurchasePrice>`
  To redefine the purchase price of an VaultType
* `/ivc Vaults VaultType Manage <VaultType> SharedAccessAmount <newSharedAccessAmount>`
  To redefine the amount of shared accesses of an VaultType
* `/ivc Vaults VaultType Manage <VaultType> TogglePurchase`
  To toggle if the VaultType is purchasable
<br>

## Symbols:
- <> = Required
- [] = Optional
- | = Or
