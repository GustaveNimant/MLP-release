## Naming Convention



1. CamelCase

2. dromedaryCase : shared modules' functions (exported) (JS)

3. snake_case : internal 

4. kebbab-case : for url smug

global constant = in UPPERCASE


### order do matter  ...

 snake_case or case_snake ?

 verb + nom  = function name
 nom + verb  = variable name

 Ex: 
 accept_input (action) : "input" is important (function name)
 input_accept          : "accept" is important (variable name)
 
### propositions :

  globals can have the source scope in their names...
  
  const FRIENDS
  var global_friends_map ("statefull") 
  let local_friends_map (temporary : "stateless")
  main_vname_map
  ipfs_run_var 

  source_var  -> implies it is global variable from source origin

  friends_reg



  sig_i ->(OOOO)-> sig_b ->[v]-> sig_q -> (OOOOO) -> sig_o 



