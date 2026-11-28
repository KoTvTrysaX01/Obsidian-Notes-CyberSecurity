Data, devices, networks, and resources are up, accessible, and working correctly when authorized users need them.
## Availability Measured in Nines
* Three nines (99.9%) allows 8.76 hours of downtime per year.
* Four nines (99.99%) allows 52.6 minutes of downtime per year.
* Five nines (99.999%) allows only 5.26 minutes of downtime per year.
More nines promised require more redundancy and engineering to deliver that level of availability.

## Three Reasons High Availability Matters
* To ensure business continuity
* To maintain customer trust
* To protect an organization's reputation*

## [[Redundancy]]
Having duplicate components ready to take over if the primary one fails
### For Major Types of Redundancy
* Server redundancy: Uses multiple server behind load balancers with failover configurations, allowing another server to take over if one crashes or becomes overwhelmed.
* Data redundancy: Storing copies of data in more than one place.
	* RAID arrays
	* Replicated databases
	* Combination of on-premises and cloud backups
	* 3-2-1 Backup Strategy: 3 copies of Your Data, 2 Different Media, 1 Offsite Copy
* Network redundancy: Provides multiple paths for data to travel.
* Power redundancy: Uses backup power sources like UPS units, and diesel generators to keep systems running during a utility outage.
	* Modent data centers use at least N+1 power redundancy, with one extra unit beyond the required load.
## [[Fault Tolerance]]
A system's ability to keep operating, often at reduced capacity, even when one or more components fail.
## [[Resilience]]
The broader ability of a system to recover quickly from distruption, whether that distruption is a hardware failure, a cyberattack, or a natural disaster.
# Key Takeaway
* Availability ensures that data and systems are ready for use when authorized users need them.
* Redundancy is the primary tool for delivering availability.

#OBJ_1_1 #CIA_Triad