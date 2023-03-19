
# Permissions
Here is a list of all the permissions that can be used
<br>

* `insanevaults.admin.openGUI`
  Be able to open the Admin GUI
* `insanevaults.admin.manageSettings`
  Be able to manage the InsaneVaults Settings
  through the Admin GUI
* `insanevaults.admin.manageFeatures`
  Be able to manage the Features through
  the Admin GUI
* `insanevaults.admin.manageUsers`
  Be able to manage Users through the Admin GUI
* `insanevaults.admin.manageVaults`
  Be able to manage Vaults through the Admin GUI
* `insanevaults.admin.manageImport`
  Be able to manage Import Data from different
  Plugins through the Admin GUI
* `insanevaults.admin.manageVaultType`
  Be able to manage Vault Types through the Admin GUI
* `insanevaults.command.vaults`
  Be able to use `/Vaults`
* `insanevaults.command.vaults.user`
  Be able to use `/Vaults <User>` to open
  the UserView of the provided User
* `insanevaults.command.vaultQuickAccess`
  Be able to use the QuickAccessCommand (Default: `/pv`)  
* `insanevaults.command.ivc`
  Be able to execute the `/ivc` command to manage
  every aspect of InsaneVaults 
* `insanevaults.command.ivc.settings.changeIconFee`
  Be able to manage the change Icon Fee through
  the `/ivc Settings ChangeIconFee <Fee>` command 
* `insanevaults.command.ivc.settings.changeNameFee`
  Be able to manage the change Name Fee through
  the `/ivc Settings ChangeNameFee <Fee>` command   
* `insanevaults.command.ivc.settings.itemDepositFee`
  Be able to manage the Item Deposit Fee through
  the `/ivc Settings ItemDepositFee <Fee>` command   
* `insanevaults.command.ivc.settings.itemWithdrawFee`
  Be able to manage the Item Withdraw Fee through
  the `/ivc Settings ItemWithdrawFee <Fee>` command    
* `insanevaults.command.ivc.settings.createSharedAccessFee`
  Be able to manage the create Shared Access Fee through
  the `/ivc Settings CreateSharedAccessFee <Fee>` command   
* `insanevaults.command.ivc.settings.transferOwnershipFee`
  Be able to manage the transfer Ownership Fee through
  the `/ivc Settings TransferOwnershipFee <Fee>` command   
* `insanevaults.command.ivc.settings.vaultTypeFees`
  Be able to manage the to be paid Vault Type Fees Settings
  through the `/ivc Settings VaultTypeFees <Option>` command     
* `insanevaults.command.ivc.settings.puttingOnGovernment`
  Be able to manage if Fees and Costs should be put on the
  UltraEconomy's Government Account through the 
  `/ivc Settings PuttingCostsAndFeesOnGovernment <True | False>` command  
* `insanevaults.command.ivc.settings.refundFees`
  Be able to manage if Vault Type Fee and paid Fees for
  created Shared Accesses should get refunded at deleting
  a Vault through the `/ivc Settings RefundFees <True | False>` command
* `insanevaults.command.ivc.features.communityVault`
  Be able to manage the Community Vault Feature through
  the `/ivc Features CommunityVault <Option>` command
* `insanevaults.command.ivc.features.vaultExtendsInventory`
  Be able to manage the Vault extends Inventory Feature through
  the `/ivc Features VaultExtendsInventory <True | False>` command
* `insanevaults.command.ivc.features.customAlias`
  Be able to manage the Custom Command Alias Feature through
  the `/ivc Features CustomCommandAlias <Option>` command
* `insanevaults.command.ivc.features.vaultPurge`
  Be able to manage the Vault Purge Feature through
  the `/ivc Features VaultPurgeFeature <Option>` command
* `insanevaults.command.ivc.vaults.createUnpaid`
  Be able to create a new unpaid Vault for specified
  User through the `/ivc Vaults CreateUnpaid <User> <VaultType>` command
* `insanevaults.command.ivc.vaults.vaultType`
  Be able to create new and delete existing 
  Vault Types through command
* `insanevaults.command.ivc.vaults.vaultType.manage`
  Be able to manage VaultTypes through the 
  `/ivc Vaults VaultType Manage <Option>` command
* `insanevaults.vault.interact.deposit.item`
  Be able to deposit items to vaults
* `insanevaults.vault.interact.withdraw.item`
  Be able to withdraw items from vaults
* `insanevaults.vault.create`
  Be able to purchase paid vaults
* `insanevaults.vault.limit.[Number]`
  Specify the amount of Vaults a User can hold
  at the same time (Replace [Number] with e.g 5)
* `insanevaults.vault.limit.bypass`
  Be able to bypass the optionally configured
  Vault limit
* `insanevaults.vault.create.unpaid`
  Be able to create unpaid vaults for yourself and other users
* `insanevaults.manageVaults.sizeLimit.bypass`
  Be able to bypass the Size limit of Vaults
* `insanevaults.manageVaults.fees.own.bypass`
  Be able to bypass Fees while interacting with own Vaults
* `insanevaults.manageVaults.fees.others.bypass`
  Be able to bypass Fees while interacting with Vaults from other Users
* `insanevaults.manageVaults.viewMoreVaultInformation`
  Be able to view more detailed information about the vault
  (When the vault was created and last time accessed)
* `insanevaults.manageVaults.manageSettings`
  Be able to manage the settings of other vaults than your vault
* `insanevaults.manageVaults.depositInOther`
  Be able to deposit items in other vaults than your own vault
  if you haven't got access through the holder of this vault
* `insanevaults.manageVaults.withdrawFromOther`
  Be able to withdraw items from other vaults than your own vault
  if you haven't got access through the holder of this vault
* `insanevaults.manageVaults.vaultTypeBlacklist.bypass`
  Be able to bypass the item blacklist of vault types at depositing items
* `insanevaults.manageVaults.userBlacklist.bypass`
  Be able to bypass the user item blacklist at depositing items
* `insanevaults.manageVaults.lockState.view`
  Be able to view the current lock state of vaults
* `insanevaults.manageVaults.lockState.manage`
  Be able to change the current lock state of vaults which is not your own vault
* `insanevaults.manageVaults.lockState.bypass`
  Be able to bypass the lock state which can usually hold
  you back from depositing or withdrawing items
* `insanevaults.manageVaults.openOthers`
  Be able to open other vaults if you haven't got access
  from the original holder of the vault
* `insanevaults.manageVaults.deleteOthers`
  Be able to delete other vaults
