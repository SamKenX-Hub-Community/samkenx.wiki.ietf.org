---
title: BESS WG - BGP Enabled ServiceS
description: This wiki is for the BESS WG.
published: true
date: 2023-07-05T12:39:02.996Z
tags: 
editor: markdown
dateCreated: 2022-11-05T16:17:26.188Z
---

# BESS WG detailed Status


## Critical items (<span style="color:red">RED FLAG</span>)
* Consistency checks required between editors of BESS YANG models to ensure a similar way of configuring and operations VPN models.

## Items to note

* YANG models: there are some dependencies with other models (BGP...).


## On going polls
| Document Name | Poll type | Chair in Charge | Start date | End date | Comment | 
| --- | --- | --- | --- | --- | --- |
| 
{.dense}



## Action items
This section lists actions other than document updates

| Action | Owner | Start date | Expected date | Done|
| --- | --- | --- | --- | --- | 



## Early allocations

| Document Name | Request date (by authors) | Status | AD approval date | IANA first allocation date | Renewal date | Expiration date |
| --- | --- | --- | --- | --- | --- | --- |
|draft-ietf-bess-mvpn-evpn-aggregation-label|12/11/18|Allocated|12/19/18|01/23/19|11/19/20 |01/23/22|
|draft-ietf-bess-evpn-bum-procedure-updates | |Allocated||02/17/17|02/06/20|02/17/21|
|draft-ietf-bess-evpn-ipvpn-interworking] |07/03/19|Allocated|07/05/19||05/26/20|07/08/21|
{.dense}


## Latest RFCs
* None since last IETF


## Documents in RFC editor queue

* draft-ietf-bess-evpn-bum-procedure-updates) (MISSREF – waiting on draft-ietf-bess-evpn-aggregation-label)
* draft-ietf-bess-evpn-optimized-ir (MISSREF – waiting on draft-ietf-bess-evpn-bum-procedure-updates)
* draft-ietf-bess-evpn-lsp-ping 

## Documents sent to IESG
Shepherd's name indicated within parenthesis.
* draft-ietf-bess-vpls-multihoming (Matthew): EXPIRED
* draft-ietf-bess-evpn-irb-mcast (Mankamana)
* draft-ietf-bess-mvpn-evpn-aggregation-label (Stephane)
* draft-ietf-bess-evpn-virtual-eth-segment (Luc Andre)
* draft-ietf-bess-evpn-pref-df (Stephane)
* draft-ietf-bess-evpn-fxc (Stephane)
* draft-ietf-bess-pbb-evpn-isid-cmacflush-06 (Matthew)
* draft-ietf-bess-bgp-sdwan-usage (Matthew)


## Documents under Shepherd's review

- draft-ietf-bess-evpn-redundant-mcast-source (Mankamana)
	- RTGDIR review in progress
  - updating the writeup this week, new refresh came just now 

- draft-ietf-bess-evpn-mh-pa (Stephane)
  - Authors replied to RTGDIR review, Ketan needs to confirm that updates are fine

- draft-ietf-bess-evpn-mh-split-horizon (Shepherd to allocate)
  - RTGDIR review requested

- draft-ietf-bess-evpn-unequal-lb (Stephane):
  - the document has a lot of normative dependencies that are not ready yet
  - Review requested to IDR chairs

- draft-ietf-bess-evpn-geneve: (Matthew)
  - Comments have been addressed

* draft-ietf-bess-evpn-fast-df-recovery (Matthew)


## Documents that failed Working Group Last Call 

- draft-ietf-bess-evpn-l2gw-proto:
	- no objection during WGLC but too few replies from WG
  - Implementations exist

- draft-ietf-bess-evpn-ipvpn-interworking:
  - need feedback from IDR chairs on aggregation rules and attribute propagation.
  - Authors needs to address IDR chair's comments


## Documents candidates for Working Group Last Call


* draft-ietf-bess-evpn-ac-aware-bundling
	- RTGDIR review requested
* draft-ietf-bess-evpn-per-mcast-flow-df-election
	- RTGDIR review requested
* draft-ietf-bess-extended-evpn-optimized-ir-03 
	- RTGDIR review requested
* draft-ietf-bess-rfc7432bis
	- RTGDIR review requested
* draft-ietf-bess-evpn-irb-extended-mobility (failed before, retry needed):
	- RTGDIR review requested
 
## Recently adopted documents

* draft-brissette-bess-evpn-vpws-seamless (6/14)
* draft-sajassi-bess-secure-evpn (6/20)

## Documents candidates for Working Group adoption


* draft-sr-bess-evpn-dpath-01
* draft-sajassi-bess-evpn-ip-aliasing-04
* draft-thubert-bess-secure-evpn-mac-signaling
* draft-duan-bess-mvpn-ipv6-infras
* draft-burdet-bess-evpn-fast-reroute

## Documents that failed WG adoption
* draft-wang-bess-sbfd-discriminator


## Working group document status (Non Expired only)

| Document Name | Last Update |  Status |
| --- | --- | --- |
|draft-ietf-bess-evpn-bfd-03 | 3/2/23 |   |
|draft-ietf-bess-ipv6-only-pe-design-03 |3/6/23| waiting for authors comment |
|draft-ietf-bess-end-system-requirements-00 | 3/6/23 | parked document |
|draft-ietf-bess-evpn-modes-interop | 3/6/23 | Expired, checking with authors |
|draft-ietf-bess-evpn-mvpn-seamless-interop-04 | 6/30/23 |authors working on updating the draft |
|draft-ietf-bess-mvpn-evpn-sr-p2mp | 3/6/23 | Update in progress based on SPRING WG comments |
|draft-ietf-bess-weighted-hrw-00| 6/1/23 | update in progress |
|draft-ietf-bess-bgp-multicast-05 |6/30/23| new update posted |
|draft-ietf-bess-secure-evpn-00  | 6/30/23 | recently adopted |
| draft-ietf-bess-ebgp-dmz-03  | 6/30/23 | Discussion with IDR to be solved |
|draft-ietf-bess-evpn-vpws-seamless-00 | 6/30/23 | recently adopted |
| draft-ietf-bess-evpn-geneve-06  | 6/30/23 | waiting for implementation |


{.dense}



## IDR/BESS cross WG reviews 
https://trac.ietf.org/trac/idr/wiki/Feedback%20for%20BESS%20drafts


&nbsp;
&nbsp;
&nbsp;

---

*The content of this page was last updated on 2022-08-04. It was migrated from the old Trac wiki on 2023-01-12.*