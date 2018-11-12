# Election Systems with Crowdsourcing Strategies


## Abstract
Modern election systems are vulnerable to various types of fraud.  Fraud can be perpetrated by voters and administrators of the election system.  A system which is secure against various types of fraud is considered to be hardened.  A crowdsourcing strategy reaps the benefits of as many volunteers as possible.

## Background
Many people have always been concerned with fraudulent voting systems throughout history.

### Voter Fraud
Voter fraud consists of ineligible people voting in one way or another.  The most obvious case of this is when dead people somehow vote in the election.

### Administrator Fraud
Administrator fraud might occur when the system has reliability problems in one way or another.  Electronic and non-electronic systems might become compromised.

### Overall Inefficiencies
Many, most, and maybe even all modern election systems have no way of validating votes against all kinds of voter fraud.

## Crowdsourcing Strategies
There are some basic protocols and processes which can harden the election system and facilitate crowdsourcing strategies.

### Authentication, Authorization, and Validation
There is a process and protocol by which an individual obtains a ballot used in the election system.  A person who wishes to vote provides the required information about their identity.  In order to facilitate crowdsourcing we require surveillance technologies which record every person involved in the process by which individuals obtain and submit ballots.  These recordings can be analyzed by crowds of people using various methods of their own to harden the process against fraud and provide evidence against individuals who attempt to perform fraud.  Combined with strict penalties against people who perform fraud, this process will reduce the occurrence of fraud in the process by which people obtain and submit ballots.

Upon submission of the ballot, voters can optionally receive a receipt with a randomly generated universally unique identifier (UUID) which corresponds with the submitted ballot.  The UUID can then be used to verify vote counting using crowdsourcing technologies and strategies.  I have done this in the past by using unique write-in candidate names as my ballot identifier.  I was then able to discover that many of the results had never been reported by the election system administrators and called into question whether or not my ballot had been counted.

## Conclusion
We can harden the election system against fraud by modifying the process to include a few additional technical components.  We can also begin to port the process to a more robust digital format where designated voting locations can emerge at any location which meets technical requirements.

Imagine using a few electronic devices to submit your vote within the comfort of your home. Two or more people follow a series of steps using technology to perform their vote in such a way that crowd sourcing strategies can be used.  Each person records the process by which they identify each other in the presence of at least one peer.  This recording is submitted and at some point in the future a ballot (digital or non-digital) with a UUID is provided to the voters.  The ballot is completed and a recorded process is used to submit the ballot and optionally obtain a receipt with the UUID for that voter's ballot.

A voter should keep their UUID secret if they wish to maintain anonymity.

## References

Imagination and Experience
