# Website for CS4756

Website: https://www.cs.cornell.edu/courses/cs4756/2023sp/

## How to update the CS4756 website

SSH to server using your NETID (make sure to get access)
```bash
ssh netid@linux.coecis.cornell.edu
```

Go to course folder
```bash
cd /cs/courses/cs4756/2023sp
```

When in doubt, nuke whatever is there
```bash
rm -rf *
rm -rf .git
```

Clone repository. But since `index.html` should be in the current folder, you need to clone the repo one level down
```bash
git clone git@github.com:sanjibanc/cs4756_sp23.git .
```

