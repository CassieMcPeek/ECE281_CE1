ECE281_CE1
==========

Cassie's Awesome Circuit

# Stimulus Process
  stim_proc:process
  begin
    ## First line of the truth table
        A <= '0';
        B <= '0';
        C <= '0';
        wait for 100 ns;
        
    ## Second line of truth table
        A <= '0';
        B <= '0';
        C <= '1';
        wait for 100 ns;
        
    ## Third line of truth table 
        A <= '0';
        B <= '1';
        C <= '0';
        wait for 100 ns;
        
    ## Fourth line of truth table
        A <= '0';
        B <= '1';
        C <= '1';
        wait for 100 ns;
        
    ## Fifth line of truth table
        A <= '1';
        B <= '0';
        C <= '0';
        wait for 100 ns
        
    ## Sixth line of truth table
        A <= '1';
        B <= '0';
        C <= '1';
        wait for 100 ns
        
    ## Seventh line of truth table
        A <= '1';
        B <= '1';
        C <= '0';
        wait for 100 ns
        
    ## Eighth line of truth table 
        A <= '1';
        B <= '1';
        C <= '1';
        wait for 100 ns;
        
        
      
