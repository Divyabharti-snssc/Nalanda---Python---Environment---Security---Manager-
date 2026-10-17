# -------------------------------------
# [STUDENT INTERNSHIP 'S PROJECT DETAILS]

# [STUDENT NAME : DIVYA BHARTI]
# [COURSE : (BSC 5th SEMESTER)]
# [SESSION : (2024-2028)]
# [UNIVERSITY ROLL NUMBER : (24281200454)]
# [UNIVERSITY REGISTRATION NUMBER : 24120023228]
# [COLLEGE NAME : S.N.SINHA COLLEGE]

# [INSTITUTE NAME : NALANDA IT Zone]
# [APPLICATION NAME : (2PFWM0BB)]
# [PROJECT TOPIC : PYTHON VERSION ENVIRONMENT & SYSTEM SECURITY MANAGER.]
# -------------------------------------

import os
import sys
import time
import shutil 


class class Environment Manager:
     def _ init _ (self):
         self.system _ status = "SECURE"
         self.system _ sandbox = None

      def display _ system _ info(self) :
          Print("---------------------------------------------")
          Print(f"[*] Python Executable Path : {sys . executable}")
          Print(f"[*] Core Version Runtime : {sys . Version . Split()}")
          Print(f"[*] Operating System Platform : {sys . Platform . Upper()}")
          if Sys . base _ prefix ! = sys . prefix : 
             Print("[*] Current Envolvement : ISOLATED (Virtual Env Active)")
           else : 
                Print("[*] Current Envolvement : GLOBAL (Hostel System Layer)")
            Print("----------------------------------------------")
      
        dif run_Poisoning_Scan(Self) :
            Print("\n[+] INITIATING HOST SYSTEM POISONING SCAN...")
            Print("[*] Scanning global Site - packages for architecture conflicts...")
            time.sleep(1.5)
            If sys.base_prefix == sys.prefix :
            Print ("[!]RISK ALERT : GLOBAL environment detected.")
            Print("[!]Hazard Level : High risk Host System Poisoning.")
            Print([*] Recommendation : Deploy an isolated Virtual Environment Informatics immediately.")
            self.system_status = "VULNERABLE "
       else : 
             Print("[✓] SCAN COMPLETE : system architecture is perfectly isolated.")
             self.system_status = "SECURE"
        dif  generat_security_bypass(self) :
             Print("\n[+] POWERSHELL DEPLOYMENT & SECURITY SEAL MODULE")
             Print("-----------------------------------------------")
             Print("[*] Status : Overcoming Windows Script Execution Policy Restriction.")
             Print("[*] To Authorize local script execution apply this command in administrative terminal:")
             Print("\n Set-Execution Policy-Execution-policy Remote Signed -Scope Process")
             Print("\n[✓] System Sell Status : deployment policy generated successfull.")
             Print("-----------------------------------------------")

           dif execute-targeted-creation(self, env_name = " sandbox_env"):
               self.active_sandbox = env_name
               Print(f"\n[+] INITIATING IARGEIED ENVI (REATION SPELL")
               Print(f"\n[+] INITIATING TARGETED ENVI_CREATION SPELL")
               Print(f"[*] Target Direction:{ os.path. join (os.getcwd(),env_name)}")
               print("[*] Executing environment isolation process.please wait...")


               try:
                   os.system[f"{sys.executable} -m venu {env_name}")
                   Print(f"[✓] Success: Isolated chamber ' { env-name} established.")
          def except _Exception ase:
                    Print(f"[x] Failure: Env generation crashed due to:{stre(e)")
                def execulte_total_exasure(self):
                    Print("\n[+] INITIATING TOTAL SYSTEM ERASURE METHOD")
                    if self. active_sandbox and os. path. exists self. active._sandbox):
                    Print(f"[*] Target
for deletion: {self. active_sandbox}
                    confirm = input("[?] Are you sure you want to completely erse the sandbox environment(y/n):")
                    if Confirm. Lower()=='y':
                    Print("[*] Reverting changes wiping environment logs and structiones...")
    
                       time.sleep(2)
                       try: 
                        shutil.rmtree(self.active_sandbox)
                   Print("[✓] success: Total Erasure Complete.Host system reverted to clean  state:")
                          self.active_sandbox = None
                  except Exception as e: 
                      Print(f"[x] Error during Erasure: {strle}")
              else:      
                    Print(f"[x] Erasure aborted environment remains locked in place.")
         else:
              Print("[!] Error: No active sandbox environment found to erase.")

    dif main():
        manager = class Environment Manager()
        While True:
              Print("------------------------------------------")
              Print("SECURE PYTHON ENVIRONMENT UTILITY")
              Print("--------------------------------------------")
              Print(" 1. Check Core Environment Profile")
              Print(" 2. Ran Host System Poisoning Scan
              Print(" 3. Generate Power Sales Security Sell Override")
              Print(" 4. Deploy Isolated Virtual Environment")
              Print(" 5. Execute Total System Erasure")
              Print(" 6. Exide Terminal Application")
              Print("---------------------------------------------")

              choice = input("[>] Select system operational (1-6):")
              if choice == '1'
                  manager. display _system_info()
                  input("\n Press Enter to continue...")
                  
            elif choice == '2':
                 manager.disply_system_info()
            
                  input("\n Press Enter to continue...")
            elif choice == '3':
                  manager.generate_securty_bypass()
                  input("\n Press Enter to continue...")
            elif choice == '4': 
                name = input("[>] Enter environment folder name ( Deficult: sandbox _env:")
                if not name.strip():
                   name == "sand_env"
                Manager.execute_targetef_creation(nume)
                input("\n Press Enter to continue...")
            elif choice == '5':
                manager.excute_total_erasure()
                input("\nP Press Enter to continue...")
            elif choice == '6'
                Print("\n[-] Shutting down secure environment manager. session closed.")
                break
            else:
                 Print("\n[x] Invalid selection choose a valied operation matric(1-6).")
                 time. sleep(1.5)


 ## Thank You 🌿
            
        Respectful thanks to the teacher for guidance and checking my project file     
          
               
         
         
         


