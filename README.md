# OxChain-Project
http://oxchain.uk/



This is a short guide of the smart contracts for the UI designers. This document will be extended shortly. 


Functions should be included in a UI:

1-	In Token_contract:

    1.1-	register_valid_contract (address valid_contract)
  
    1.2-	assign_token_to_donor (address reciever, uint amount)
  
    1.3-	send_Eth (address donor_addr)

    1.4-	buyToken()
  
    1.5-	get_donor_total_locked_tokens (address _donor_addr)
  
    1.6-	assign_token_to_contract (uint _amount, address _master_contr_addr, bytes6 pro_id)
  
    1.7-	destroy()

2-	In Master_contract:

    2.1-	add_beneficiary (address _ben_addr)
  
    2.2-	add_validators (address _validator_addr)
  
    2.3-	set_project (string description,  address _deneficiaries_addr, uint val_period, uint cancelation_period)
  
    2.4-	validate_project (uint _index, bool res)
  
    2.5-	cancel_project (bytes6 project_id)
  
    2.6-	remove_an_expired_project (bytes6 _pro_id)
  
    2.7-	remove_all_expired_projects ()


