# PayUp Basics
Before you start working with and using PayUp, we recommend you read this page to take a look at how PayUp works and how it will benefit your online business.

## Payment Handling
PayUp works with [Stripe ↗](https://stripe.com) and [PayPal ↗](https://paypal.com) to help transform your Discord Server into a functioning store.

We work closely with both Stripe and PayPal to ensure you and your customers are getting a premium experience, with no added costs. These two providers were handpicked as they are not only reputable but also advanced and easy to configure.

## How does PayUp work?
PayUp simplifies payment processing within your community by integrating directly with Stripe and PayPal, allowing you to easily manage and track transactions directly from your Discord Server. You can see a breakdown of how PayUp works below.

!!! example "Subject to Change"
	This information is subject to change at any moment in time, and may not be accurate to the current state of PayUp.

1. Checkout Creation:
	To start a payment, you can use PayUp's `/product` command.
	This will contact the payment provider selected by the user (based on your server configuration) and create a payment link, allowing users to securely complete their transactions.
2. Transaction Updates:
	Once the payment link is generated, PayUp tracks the status in real-time. Whether the payment is completed, pending, cancelled or expired - the bot will keep you informed at all times using your configured logging channel.
3. Checkout Experience:
	PayUp ensures that customers are utilising secure checkout pages provided by Stripe and PayPal. After completing their transaction, they are redirected back to the channel where the payment was initiated. PayUp will provide confirmation messages and updates about the payment in that channel alongside the logging channel.
4. Analytics and Insights:
	PayUp retains records of all transactions, allowing you to view and monitor sales performance.

## Disputes and Refunds
1. Understanding Refunds:
	Since PayUp is a bridge between your server and the [payment processors ↗](#payment-handling), it only handles information regarding the payment process. This means that we have no way of providing refunds or managing disputes. This means we rely on the seller to manage refunds and disputes.
	* Seller Responsibility:
		As a seller, you have control over refund policies and how they are implemented. This means you can setup a custom refund policy that best suits your business. When a refund is requested, you are to handle that directly via Stripe or PayPal inline with their respective guidelines.
	* Processor Rules:
		Regardless of your own policy (or policies), refunds must remain compliant with the rules and proceedures of Payment Processors. These platforms may require you to issue refunds under certain circumstances, such as for unauthorized transactions or in the event of buyer protection claims.
	* Setting Clear Expectations:
		It is important that you are transparent with your refund policy, and that buyers are constantly made aware. We recommend having it publicly accessible on your Discord Server so customers can know what to expect and reduce the likelihood of misunderstandings or disputes.

2. Handling Disputes
	Disputes occur when customers challenge a charge, which may lead to **chargebacks**. As with refunds, PayUp cannot and will not intervene in disputes - however, we do have some tips to assist you in managing them effectively.

	!!! tip
		The PayUp Team *may* be able to provide either of the parties involved with further information about the transaction, if identities can be verified and tracked back to the request.
	* Constant Monitoring:
		If a dispute arises, Stripe or PayPal will notify you of this directly. Both platforms provide tools and guidance to help you respond to disputes and *potentially* resolve them in your favor.
	* Provide Evidence:
		To improve your chances of winning a dispute, you should gather and relevant transactions details, communications or proof of delivery. This information should be submitted to Stripe or PayPal as part of the dispute resolution process.
	* Remaining Transparent:
		Maintaining an honest and open communication with your customers can easily prevent disputes. Let your customers know how and where to reach out for help, and constantly address issues in a timely manner before they escalate into disputes.

3. What PayUp does and doesn't do
	It is critical that you understand the role of PayUp in these processes.
	* Does:
		PayUp will update the statuses of payments within Discord. This ensures that everybody is informed and ensures transparency.
	* Doesn't:
		PayUp has **no control** over refund and dispute processes. All actions regarding refunds or disputes are carried out seperately from PayUp via your Stripe/PayPal accounts.
		
## How do I start using PayUp?
We have tried extremely hard to keep the setup process as simple as possible. All you have to do is invite the bot to your server, create your PayPal Business/Stripe Seller account(s) and configure them with the bot.

!!! tip
	To assist with setup, we have created a special [setup page ↗](/docs/Setup-Guide/initial-setup) for you to follow!