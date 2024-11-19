# Module 4 challenge: Securing Your Networks


1. **Question 1**: What traffic does an implicit deny firewall rule block?  
   **Answer**: All traffic that is not explicitly permitted or allowed

2. **Question 2**: Which enterprise switch features protect against layer 2 man-in-the-middle attacks? Select all that apply.  
   **Answer**:  
   - DHCP Snooping  
   - IP Source Guard  
   - Dynamic ARP inspection (DAI)

3. **Question 3**: Your company hires remote workers and wants them to be able to securely access company resources from their remote locations. What solution(s) would you recommend they consider? Select all that apply.  
   **Answer**:  
   - VPN  
   - Reverse proxy

4. **Question 4**: Multiple vulnerabilities in the WEP protocol make it possible for the encryption key to be recovered by hackers. Which parts of the WEP protocol create this vulnerability? Select all that apply.  
   **Answer**:  
   - The initialization vectors, and therefore the encryption keys, were weak and reused too often.  
   - In open-system WEP authentication mode, the client can be authenticated by the Access Point (AP) without passing the decryption challenge.  
   - In shared-key WEP authentication mode, the Access Point (AP) shares both the plaintext and the ciphertext with the client.

5. **Question 5**: What makes the WPS method of PIN entry authentication with a hard-coded pin vulnerable to online brute force attacks?  
   **Answer**: It uses an 8 digit PIN, which is made of 7 digits and one checksum value, and sends it in two parts. This means it takes a maximum of 11,000 tries to guess the PIN.

6. **Question 6**: What tool can you use to ensure that WPS is disabled on your APs?  
   **Answer**: Wash

7. **Question 7**: You’re an IT support specialist and you’ve been tasked with making sure the company is monitoring its network traffic adequately. What technique should you use if you want to access all packets from a specified port, port range, or entire VLAN?  
   **Answer**: Port mirroring

8. **Question 8**: You’re an IT support specialist tasked with setting up a NIDS system to monitor your company’s network traffic for suspicious behavior. Which of the following options would you implement? Select all that apply.  
   **Answer**:  
   - Set up the NIDS host with two network interfaces; one for analysis and one for management.  
   - Enable promiscuous mode on the NIDS analysis port.  
   - Use port mirroring to mirror all network traffic to the NIDS host

9. **Question 9**: You want to use tcpdump to retrieve packets with 100.1.4.3 as the source or destination IP address and any port as the source or destination port. Which command should you use?  
   **Answer**: sudo tcpdump -i eth0 -vn host 100.1.4.3

10. **Question 10**: When you run the command sudo tcpdump -i eth0, what output does tcpdump provide about each packet? Select all that apply.  
   **Answer**:  
   - The layer 3 protocol, source, and destination addresses and ports.  
   - TCP details.  
   - Service names commonly associated with the detected port numbers.  
   - IP header details.
