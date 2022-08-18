# W-11603879 - 42960787 - Amazon Web Services - Combobox Dropdown Overflow Behind Parent Combobox in Modal

# Repro
- Clone this repo
- Push to a scratch org
- Override New Opportunity with auraContainer
- Create a new Opportunity

Observe the dropdowns duck behind the footer

If you add 'uiModal' to the class list for the slds-modal section (in lwcParent), the problem is solved.