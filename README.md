# Lunch Money Shortcuts
Here are some iOS Shortcuts I use to use interact with Lunch Money from my iPhone.  

⚠️ For both shortcuts, you will need to provide your Lunch Money API key the first time (get your API key [here](https://my.lunchmoney.app/developers)).  
⚠️ For the second shortcut, you will also need to previde the category id of your 'Transfer' category (get your category id [here](#how-to-get-the-category-id-for-the-transfer-category)).  
The API Key and Category id are saved to iCloud storage and used for future runs of the shortcut.

- Add a transaction ([link](https://www.icloud.com/shortcuts/ab60ff7e9f6c48488784d3e8dff1c749)):
  - Select the source account.
  - Select the category.
  - Enter the amount.
  - Enter the payee.
    
- Add a transfer ([link](https://www.icloud.com/shortcuts/2093785feb22458ab0e300e710e9238b)):
  - Select the source account.
  - Select the destination account.
  - Enter the amount that will be debited on the source account.
  - If the default currency of both accounts is different, enter the amount that will be credited on the destination account.


#### How to get the category id for the Transfer category
The 'add a transfer' shortcut will set as category the 'Payment, Transfer' category. For this it needs the correct category id.  
To find the category id:
- Go to your categories page: https://my.lunchmoney.app/categories.
- Click on the magnifier icon on the right side of the line of your transfer category.
- Click on the green "View Transactions" button.
- The URL of the opened page should be like this: `https://my.lunchmoney.app/transactions/year/month?category=XXXXXXX&match=all&time=all`
- The category id is the `XXXXXXX` part.



### Acknowledgments
I took inspiration from [jamiepinheiro](https://github.com/jamiepinheiro/lunch_money_categorize_transaction_shortcut) to build those shortcuts.

### Disclaimer
These iOS shortcuts are provided "as is" without any warranties. I am not responsible for any damage, data loss, or issues that may arise from their use. Use them at your own risk and discretion.
