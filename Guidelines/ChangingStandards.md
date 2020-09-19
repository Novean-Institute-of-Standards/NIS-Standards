# Changing Standards

The guidelines for submitting a modification to the NIS Standards.

- [What is a SIP?](#what-is-a-sip)
- [SIP Types](#sip-types)
- [SIP Workflow](#sip-workflow)

## What is a SIP?

SIP stands for Standards Improvement Proposal. A SIP is a design document providing information to NIS describing a new standard, recommendation, or a change to an existing standard. The SIP should provide a concise specification of the feature and a rationale for the feature.

SIPs are intended to be the primary mechanisms for proposing new standards, for collecting input on an issue, and for documenting the design decisions that have gone into the NIS Standards. The SIP author is responsible for building consensus and documenting dissenting opinions.

Because standards are maintained as text files in a versioned repository, their revision history is the historical record of the NIS Standards.

## SIP Types

The following is a brief outline of the various types of SIPs, however each is covered in full detail in their respective sections.

- [**Fundamentals SIP**](WritingFormatting.md#fundamentals-sip) - Will cover a standards proposal that will be required fundamental knowledge for all users impacted. If a Fundamentals SIP is accepted, a grace period will be enacted so that users can train and/or adapt to the changes as needed. 

  An example of a Fundamentals SIP would be the usage of UTC as the base time, in which all traffic controllers and pilots would need to be adapt to communicating only in UTC time. 
  
- [**Recommendation SIP**](WritingFormatting.md#recommendation-sip) - Will cover a standards proposal for non-binding guidance or best practice recommendations. If a Recommendation SIP is accepted, it's not expected that any parties adhere to it, though it's understood that following it may lead to a better experience for impacted users.

  An example of a Recommendation SIP would be using Illuminated Voxels in a specific pattern on a landing pad to denote nearby amenities for specific ship classes. While not necessary, it may improve the pilot landing experience. 
  
- [**Emergency SIP**](WritingFormatting.md#emergency-sip) - Will cover a standards proposal for emergency changes needed to adapt to a rapidly evolving situation. Typically this type of SIP will involve many partners working together to address an issue quickly so that the impact of the situation can be minimized.

  An example of an Emergency SIP would be a change in LUA functionlity that removes a feature, or changes the way a feature works, that would require codes changes and operational changes immediately.
  
- [**Errata SIP**](WritingFormatting.md#errata-sip) - These are brief SIPs for fixing misspellings and other errors in the standards. 


## SIP Workflow

- (Errata SIPs are exempted from this workflow; see [Errata SIP](WritingFormatting.md#errata-sip))

The SIP process begins with a new idea for the NIS Standards. Each potential SIP must have a champion (someone who writes the SIP using the style and format described below and shepherds the discussions in the appropriate channels) who must attempt to build consensus around the idea.  

The SIP champion (a.k.a. Author) should first attempt to ascertain whether the idea is SIP-able. Using [Discord](https://discord.gg/jetkCs3) is the best avenue for starting this and discussing ideas with others involved.  

Vetting an idea publicly before going as far as writing a SIP is meant to save both the potential author and other contributers time. Asking the NIS community first if an idea is original helps prevent too much time being spent on something that is guaranteed to be rejected based on prior discussions.   

It also helps to make sure the idea is applicable to others and not just the author. 

Once the champion has asked the NIS community as to whether an idea has any chance of acceptance, a draft SIP should be presented to the appropriate discord #SIP-drafts channel. This gives the author a chance to flesh out the draft SIP to make it properly formatted, of high quality, and to address additional concerns about the proposal. 

Following a discussion, the proposal should be submitted for a decision by the partner standards members on discord. This draft must be written in SIP style as described below, or else it will be sent back until proper formatting rules are followed. The standards partner members will determine the impact of the proposal and notify the author. 

It is highly recommended that a single SIP contain a single key proposal or new idea. The more focused the SIP, the more successful it is likely to be. If in doubt, split your SIP into several well-focused ones.

Once a SIP has been accepted, the reference implementation must be completed with a pull request to the [Github Repo](https://github.com/Novean-Institute-of-Standards/NIS-Standards), with the SIP attached to the description field where it will be verified and merged into this document if accepted.
