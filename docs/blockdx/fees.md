title: Block DX Fee Structure
description: Block DX is a decentralized exchange dApp powered by the Blocknet Protocol that has lower fees and no deposit, withdrawal, or maker fees.


# Block DX Fee Structure
[Block DX](/blockdx/introduction) is a decentralized exchange dApp powered by the Blocknet Protocol. Unlike centralized exchanges, Block DX has no deposit, withdrawal, or maker fees other than network fees of the asset being traded.

---

## Maker Fee
When creating an order on Block DX, there is no fee other than the transaction fee for the network of the asset being sold. This is the same type of fee you would incur if sending this asset to another party.

Having no fee to place an order encourages market makers to add liquidity. This also makes it possible for a user to acquire the [BLOCK](/blockchain/introduction) needed to take orders.

---

## Taker Fee
When accepting an order on Block DX, a static fee of 0.015 [BLOCK](/blockchain/introduction) is charged at the time the order is taken. This fee is charged even if a trade is canceled or fails and is meant to discourage malicious behavior on the network. 

In addition to the 0.015 BLOCK fee, there is also the transaction fee for the network of the asset being sold. This is the same type of fee you would incur if sending this asset to another party.

If the taker asset is BLOCK, there needs to be *at least* two UXTOs - one or more to cover the 0.015 BLOCK fee and one or more to cover the traded amount. 

In a future update, there will be a percent-based fee that’s charged when accepting an order, but the details of this are not yet finalized.


---

## Fees Distribution
100% of trade fees are distributed to [Service Node](/service-nodes/introduction) operators for supporting the network.












<!-- 
======= Start: Related Links Section =======
- This is the related links section at the bottom of each page.
- It lists the links in the relatedLinks array variable below.
	Example: relatedLinks = [{"name":"Blocknet Website","link":"https://blocknet.co"},{"name":"API Docs","link":"https://api.blocknet.co"}];
- If the array is empty, ie. relatedLinks = [], then the related links section will not be displayed.
related-links.html
- The template and logic for the related links section can be found in docs/snippets/related-links.html
- The base path is defaulted to docs/snippets/, which can be edited in the mkdocs.yml file
- The template and logic is linked with markdown_extensions: pymdownx.snippets
-->
<script type="text/javascript">
var relatedLinks = [];
</script>

--8<--
related-links.html
--8<-- 
<!-- 
======= End: Related Links Section ======= 
-->





