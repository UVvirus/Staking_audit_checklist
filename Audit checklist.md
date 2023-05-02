# Staking contract audit checklist: 
- [ ]   call that stake function twice and see whether the old stake has been replaced by new stake, if yes it’s a  bug.
- [ ]   Check whether the protocol fee has been sent to owner's address and then resetted.
- [ ]   Other than investor, can anyone can withdraw all the funds
- [ ]   Can tokens be withdrawn before or during the cliff period or vesting period
- [ ]   Check whether the reward are calculated correctly
- [ ]   Check for reentrancy
- [ ]   Check for the possibility of flash loan attack
- [ ]   Staking contracts are the most vulnerable contracts to DOS
- [ ]   Try to claim the reward twice, if you can get it, then it's a bug