## v3.0 (May 2020)

IMPROVEMENTS:

* **improvement:** Remove deprecated address_prefix variable for the subnet in favour of address_prefixes (requires azurem 2.8.0 and above)
* **improvement:** Added custom nsg name option
* **improvement:** Added additonal configuration options for nsg

Introduces breaking changes in the input variable

## v2.0 (March 2020)

IMPROVEMENTS:

* **improvement:** Add support for azurecaf provider for naming convention ([15](https://github.com/aztfmod/terraform-azurerm-caf-virtual-network/issues/15))
* **improvement:** Change virtual_network_rg input variable name to resource_group_name


## v1.2 (March 2020)

IMPROVEMENTS:

* **improvement:** Get ddos_id as optional argument at module call ([13](https://github.com/aztfmod/terraform-azurerm-caf-virtual-network/issues/13))


## v1.1 (February 2020)

BUGS:

* **bug fix:** Issue with provider azurerm 2.0 ([#10](https://github.com/aztfmod/terraform-azurerm-caf-virtual-network/issues/10))

## v1.0 (January 2020)

FEATURES:

* **new feature:**  Add support for traffic analytics and Network flows ([#4](https://github.com/aztfmod/terraform-azurerm-caf-virtual-network/issues/4))
* **new feature:**  Add support for naming convention ([#5](https://github.com/aztfmod/terraform-azurerm-caf-virtual-network/issues/5))
* **new feature:**  Add support for private link policies on virtual subnets ([#8](https://github.com/aztfmod/terraform-azurerm-caf-virtual-network/issues/8)) 
* **new feature:**  Add examples for: Delegation, Simple Vnet, Simple Vnet with network watcher ([#6](https://github.com/aztfmod/terraform-azurerm-caf-virtual-network/issues/6))

IMPROVEMENTS:

BUGS:
* **bug fix:** Fix bug when a subnet has no NSG section declared, you cant create the Vnet ([#7](https://github.com/aztfmod/terraform-azurerm-caf-virtual-network/issues/7)) 
* **bug fix:** Support for eventhub logging is now optionnal ([#3](https://github.com/aztfmod/terraform-azurerm-caf-virtual-network/issues/3)) 
