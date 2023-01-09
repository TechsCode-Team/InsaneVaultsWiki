# Placeholders
Below is a list of all available placeholders. Keep in mind these placeholders require **[PlaceholderAPI](https://www.spigotmc.org/resources/6245/)** & a plugin that supports the API!
<br>

* `%ivaults_all_vaults_amount%`
  Returns the amount of all created vaults
* `%ivaults_vault_<VaultName>_size_free%`
  Returns the free slots amount of the provided vault of the user
* `%ivaults_vault_<VaultName>_size_used%`
  Returns the used slots amount of the provided vault of the user
* `%ivaults_vault_<VaultName>_vaultType%`
  Returns the VaultType name of the provided vault of the user
* `%ivaults_vault_<VaultName>_sharedAccesses%`
  Returns the shared accesses amount of the provided vault of the user
* `%ivaults_vault_<VaultName>_founder_name%`
  Returns the founder name of the provided vault the user is holding
* `%ivaults_vault_<VaultName>_founder_uuid%`
  Returns the founder uuid of the provided vault the user is holding
* `%ivaults_shared_vaults_amount%`
  Returns the amount of vaults which were shared with the parsed user
* `%ivaults_own_vaults_amount%`
  Returns the amount of vaults the parsed user is holding
* `%ivaults_founderOf_vaults_amount%`
  Returns the amount of vaults the parsed user is the founder of
* `%ivaults_is_new_user%`
  Returns if the parsed user is a new user (Requirements are specified in the CommunityVault feature)
* `%ivaults_vaultType_amount_<VaultType>%`
  Returns the amount of vaults which are based on provided VaultType
* `%ivaults_vaultType_hasAsOwn_<VaultType>%`
  Returns if parsed user has at least one own vault which is based on provided VaultType
* `%ivaults_vaultType_hasAsShared_<VaultType>%`
  Returns if parsed user has at least one shared vault which is based on provided VaultType
* `%ivaults_vaultTypes_amount%`
  Returns the amount of created VaultTypes
* `%ivaults_fee_transfer_ownership%`
  Returns the fee to transfer the ownership of an vault
* `%ivaults_fee_item_withdraw%`
  Returns the fee to withdraw an item from an vault
* `%ivaults_fee_item_deposit%`
  Returns the fee to deposit an item into an vault
* `%ivaults_fee_create_shared_access%`
  Returns the fee to create a new shared access
* `%ivaults_fee_change_name%`
  Returns the fee to change the name of an vault
* `%ivaults_fee_change_icon%`
  Returns the fee to change the icon of an vault
* `%ivaults_is_refund_fees_enabled%`
  Returns if refunding shared access fee and vault type creation cost is enabled
* `%ivaults_is_recurring_cost_enabled%`
  Returns if recurring vault type creation cost is enabled
<br>

**`NOTE:` When using a placeholder containing an argument that you need to fill (Ex. `<VaultName>`), make sure to remove the <>**

