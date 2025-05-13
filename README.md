**Q: When is the state file created?**
A: The state file (`terraform.tfstate`) is created after the first successful `terraform apply`.

**Q: When is the lock file present?**
A: The lock file (`.terraform.tfstate.lock.info`) is created temporarily during `terraform apply` and `terraform plan` to prevent concurrent modifications.

**Q: Is the lock file always in the bucket after it is created?**
A: No, it is only present during the operation and is removed once the command completes.# 4640-w13-lab-start-w25

