# base555551
Why Base Is Becoming One of the Most Active L2 Chains  Base has flipped many L2s by user count.  Python Example: compare transactions
for rpc in ["base", "optimism", "arbitrum"]:
    w3 = Web3(Web3.HTTPProvider(f"https://{rpc}.publicnode.com"))
    print(rpc, "latest block:", w3.eth.block_number)
