# Decision Records

For any architectural/engineering decisions we make, we will create an Decision Record to keep track of what decision we made and why.
This allows us to refer back to decisions in the future and see if the reasons we made a choice still holds true.
This also allows for others to more easily understand the code. Decision Records will follow this process:

- They will live in the repo, under a directory `docs/decisions`
- They will be written in markdown
- They will follow the naming convention `DR-NNNN-<decision-title>.md`
    - `NNNN` will just be a counter starting at `0001` and will allow us easily keep the records in chronological order.
- The common sections that each Decision Record should have are:
    - Title
    - Context
    - Objective
    - Options
    - Decision
    - Consequences
