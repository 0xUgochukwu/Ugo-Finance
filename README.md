# $UgoFinance

A Stock Exchange App built with Flask (Python)

## How to Run the App in your Local Environment


**NB: Make sure you have python already installed in your computer**

After cloning/downloading the App to your Local Computer, here's what you need to do to get the app running locally;

##### 1. Install the requirements

Among the files you downloaded is a `requirements.txt` file that lists the packages you need to run the app locally. In your terminal, execute:
`$ pip install [package_name]`
where `[package_name]` is the name of a package in the `requirements.txt` file.

Execute this for each package until you have installed all of them required.


##### 2. Get your API Key

* Visit [iexcloud.io/cloud-login#/register/](iexcloud.io/cloud-login#/register/).
* Select the “Individual” account type, then enter your name, email address, and a password, and click “Create account”.
* Once registered, scroll down to “Get started for free” and click “Select Start plan” to choose the free plan.
* Once you’ve confirmed your account via a confirmation email, visit [https://iexcloud.io/console/tokens](https://iexcloud.io/console/tokens).
* Copy the key that appears under the Token column (it should begin with `pk_`).
* In your terminal, execute:
`$ export API_KEY=value`
where `value` is that (pasted) value, without any space immediately before or after the `=`. You also may wish to paste that value in a text document somewhere, in case you need it again later.


#### 3. Run the App

Start Flask’s built-in web server (within the app folder):
`$ flask run`
Visit the URL outputted by flask to see the distribution code in action. You will need to `register` and `login` to use the featues of the app. 


