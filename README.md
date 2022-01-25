# Process-Version-08
<h1> DefiSafety’s Process Quality Review version 0.8 </h1>

We have added some exciting new components to our reviews. These included metrics concerning Oracles and Timelocks. In addition, we have completely re-written our background documentation, as well as rephrased the entirety of our review template in order to make it increasingly understandable for our users. Lastly, we have re-weighted much of our scoring allocations by putting a larger emphasis on Access Controls, now re-named Admin Controls.

<h1>0.8 Changelog</h1>
<h2>Process Documentation</h2>

●	All Process Documentation re-written, front to back. 

●	Added “Oracles” section

●	Added TimeLock questions in “Access Controls” section

<h2>Scoring Matrix</h2>
<br>
Section “Code and team”: Reduced scoring weight of section from 19.2% to 14.1%

●	Question 5 “Is the team public”: Changed scoring weight from 5.8% to 3.1%

●	All other scoring weights changed in relation to new point increase (0.7 had 260 points, .8 now has 320)

<br>
Section “Documentation”: Reduced scoring weight from 17.3% to 10.9%

●	Question 9 “Are there sufficiently detailed comments for all functions within the deployed contract code” was removed

●	All other scoring weights changed relative to point increase (.7 had 260 points, .8 has 320)

<br>

Section “Testing”: Reduced scoring weight from 19.2% to 15.6%

●	Question 11 “What is the documented code coverage from the tests? “: Scoring weight changed from 1.9% to 3.1%

●	Question 13 “Is there a report of the protocol’s test results?”: Scoring weight changed from 3.8% to 1.6%

●	All other scoring weights changed relative to point increase (.7 had 260 points, .8 has 320)

<br>

Section “Security”: Reduced scoring weight from 30.8% to 23.4%

●	Question 16 “Is the protocol sufficiently audited?”: Scoring weight reduced from 26.9% to 20.3%

●	All other scoring weights changed relative to point increase (.7 had 260 points, .8 has 320)

<br>

Section “Access Controls”: Increased scoring weight from 13.5% to 23.4%

●	Question 20 “Is the information clear and complete”: Was removed

●	Question 19 “Are relevant contracts clearly labelled as upgradeable?”: Was added to our reviews with a weight of 3.1%

●	Question 20 “Is the type of contract ownership clearly indicated?”: Was added to our reviews with a weight of 4.7%

●	Question 21 “Is the contract change capability described?”: Was added to our reviews with a weight of 3.1%

●	Question 22 “Is the information easy to understand?”: Scoring weight reduced from 3.8% to 1.6%

●	Question 24 “Is there sufficient Timelock documentation?”: Was added to our reviews with a weight of 3.1%

●	Question 25 “Is the timelock of an adequate length?”: Was added to our reviews with a weight of 3.1%

●	All other scoring weights changed relative to point increase (.7 had 260 points, .8 has 320)

<br>

Section “Oracles”: NEW SECTION ADDED with a weight of 12.5%

●	Question 26 “Is the Oracle sufficiently documented?”: Was added to our reviews with a weight of 6.3%

●	Question 27 “Is front running mitigated by this protocol?”: Was added to our reviews with a weight of 1.6%

●	Question 28 “Can flashloan attacks be applied to the protocol, and if so, are those flashloan attack risks mitigated?”: Was added to our reviews with a weight of 4.7%

<h2>Question Nomenclature</h2>

<br>

Section “Code and team”: Name was changed to “Smart Contracts and Team”

●	Question 1 “Are the executing code addresses readily available?” was changed to “Are the smart contract addresses easy to find?”

●	Question 2 “Is the code actively being used?” was changed to “How active is the primary contract?”

●	Question 3 “Is there a public software repository?” was changed to “Does the protocol have a public software repository?”.

<br>

Section “Documentation”: Name was changed to “Code Documentation”.
	
●	Question 7 “Are the basic software functions documented?” was changed to “Is the protocol's software architecture documented?”.

●	Question 8 “Does the software function documentation fully (100%) cover the deployed contracts?” was changed to “Does the software documentation fully cover the deployed contracts' source code?”.

●	Question 9 “Are there sufficiently detailed comments for all functions within the deployed contract code?” was removed.

●	Question 10 “Is it possible to trace from software documentation to the implementation in code?” replaced Question 9, and was changed to “Is it possible to trace the documented software to its implementation in the protocol's source code?”

<br>

Section “Testing”

●	Question 11 “Is there a full test suite?” moved down to Question 10, and was changed to “Has the protocol tested their deployed code?”.

●	Question 12 “Code coverage” moved down to Question 11, and was changed to “What is the documented code coverage from the tests?”.

●	Question 13 “Scripts and instructions to run the tests” moved down to Question 12, and was changed to “Does the protocol provide scripts and instructions to run their tests?”.

●	Question 14 “Report of the results” moved down to Question 13, and was changed to “Is there a detailed report of the protocol’s test results?”.

●	Question 15 “Formal Verification test done” moved down to Question 14, and was changed to “Has the protocol undergone Formal Verification?”.

●	Question 16 “Stress Testing” moved down to Question 15, and was changed to “Were the smart contracts deployed to a testnet?”.

<br>

Section “Security”

●	Question 17 “Did 3rd Party audits take place?” moved down to Question 16, and was changed to “Is the protocol sufficiently audited?”.
●	Question 18 “Is the bounty value acceptably high?” moved down to Question 17.

<br>

Section “Access Controls”: Name was changed to “Admin Controls”.

●	Question 19 “Can a user clearly and quickly find the status of the access controls?” moved down to Question 18, and was changed to “Is the protocol's admin control information easy to find?”

●	Question 20 “Is the information clear and complete” was separated in 3 different questions:

●	Question 19 “Are relevant contracts clearly labelled as upgradeable or immutable?”

●	Question 20 “Is the type of smart contract ownership clearly indicated?”

●	Question 21 “Are the protocol's smart contract change capabilities described?”

●	Question 21 “Is the information in non-technical terms that pertain to the investments” was moved up to Question 22, and was changed to “Is the protocol's admin control information easy to understand?”.

●	Question 22 “Is there Pause Control documentation including records of tests?” was moved up to Question 23, and was changed to “Is there sufficient Pause Control documentation?”.

●	Question 24 “Is there sufficient Timelock documentation?” was added to the reviews.

●	Question 25 “Is the Timelock of an adequate length?” was added to the reviews.

<br>

Section “Oracles” was added to the reviews.

●	Question 26 “Is the protocol's Oracle sufficiently documented?” was added to the reviews.

●	Question 27 “Is front running mitigated by this protocol?” was added to the reviews.

●	Question 28 “Can flashloan attacks be applied to the protocol, and if so, are those flashloan attack risks mitigated?” was added to the reviews.

<br>

<h2>Question Guidance</h2>

Question 5 “Is the team public (not anonymous)?”.

●	Added guidance “0%: No public team members could be found.”

●	Added guidance “50%: At least one public name can be found to be working on the protocol.”

●	Added guidance “100%: At least two names can be easily found in the protocol’s website, documentation or medium. These are then confirmed by the personal websites of the individuals / their linkedin / twitter.” 

Question 7 “Is the protocol's software architecture documented?” (Previously “Are the basic software functions documented?”).

●	Added guidance “Yes: the documents identify software architecture and contract interaction through any of the following: diagrams, arrows, specific reference to software functions or a written explanation on how smart contracts interact.”

●	Added guidance “No If none of these are included.”

Question 13 “Is there a detailed report of the protocol’s test results?” (Previously Question 14).
●	Changed “70% - GitHub code coverage report visible” to “50% - Code coverage report visible”.

Question 14 “Has the protocol undergone Formal Verification?” (Previously Question 15).

●	Added guidance “Yes - Formal Verification was performed and the report is readily available”.

●	Added guidance “No (0%) - Protocol has not proved their testnet usage by providing the addresses”.

Question 15 “Were the smart contracts deployed to a testnet?” (Previously Question 16).

●	Added guidance “Yes (100%) - Protocol has proved their tesnet usage by providing the addresses”.

●	Added guidance “No (0%) - Protocol has not proved their testnet usage by providing the addresses”.

Question 16 “Is the protocol sufficiently audited?” (Previously Question 17)

●	Added guidance “80% - Multiple audits performed after deployment and no changes required. The Audit report is public.”

●	Added guidance “65% - Code is forked from an already audited protocol and a changelog is provided explaining why forked code was used and what changes were made. This changelog must justify why the changes made do not affect the audit.”

●	Added guidance “30% - Audit(s) performed are low-quality and do not indicate proper due diligence.”







