<!--- Provide a title for the proposal in the Title above -->
<!--- Follow this template to create a proposal. -->

*Author*: Your Name <@yourGHid> IRC: handle (if different)

*Date*: 2017/{mm}/{dd}

*Status*:
  - [ ] New
  - [ ] Approved
  - [ ] Pending
  - [ ] Complete

*Proposal type*:
  - [ ] Core
  - [ ] Design
  - [ ] Process
  - [ ] Other

*Targeted Release*: <future release #, ex. 2.4>
*Associated PR*: <link to GH PR in ansible/proposals if PR was submitted>
*Estimated time to implement*: <X days, weeks, etc.>


*Proposal Meeting*:
- [ ] Tuesday @ 19:00 UTC
- [ ] Thursday @ 15:00 UTC

*Deadline for final submission of questions*:
- [ ] 2 Weeks
- [ ] 3 Weeks
- [ ] 4 Weeks
- [ ] 5 Weeks (With Core agreements)

## Motivation
Describe the reasons for this proposal.
<!--- If describing a bug, tell us what happens instead of the expected behavior -->
<!--- If suggesting a change/improvement, explain the difference from current behavior -->


### Problems
What problems exist that this proposal will solve?
- Problem #1
- Problem #2
- Or just describe the problem if there is just one.
  - If possible add ansible/ansible#PR or ansible/ansible#ISSUE of where this problem is listed
  - Example ansible/ansible#150

<!--- Provide a link to a live example, or an unambiguous set of steps to -->
<!--- reproduce this. Include code to reproduce, if relevant -->
1.
2.
3.
4.

## Solution proposal
- Describe your suggested solution here.
- Insert code in snippets if you would like as shown.
```
    - include: main.yml
      vars:
         var1: val1
```
- Be sure to explain how this solves problems.

## Dependencies (optional)
Explain any dependencies. This section is optional but could be helpful.
- Dependency #1
- Dependency #2

## Assistance
- [ ] Do you require assistance on this project
- If so, what is required?
  - [ ] Coding
  - [ ] Testing
  - [ ] Community wrangling
  - [ ] Core adoption

## Testing (optional)
Does / should this require testing, and if so, how? Describe here. This section is optional but could be helpful.

## Documentation (optional)
Does / should this require documentation? If so, describe here. This section is optional but could be helpful.

## Types of changes
<!--- What types of changes does your code introduce? Put an `x` in all the boxes that apply: -->
- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to change)

## Checklist:
<!--- Go over all the following points, and put an `x` in all the boxes that apply. -->
<!--- If you're unsure about any of these, don't hesitate to ask. We're here to help! -->

- [ ] My code follows the code style of this project.
- [ ] My change requires a change to the documentation.
- [ ] I have updated the documentation accordingly.
- [ ] I have read the **CONTRIBUTING** document.
- [ ] I have added tests to cover my changes.
- [ ] All new and existing tests passed.
- [ ] I have added my proposal to the core agenda

## Coding Checklist
<!-- In controller side code, we support Python-3.5 or greater and Python-2.6 or greater.

For modules (and by extension, module_utils) we support Python-3.5 and Python-2.4.
Python-3.5 was chosen as a minimum because it is the earliest Python-3 version adopted as the default Python by a Long Term Support (LTS) Linux distribution (in this case, Ubuntu-16.04).
Previous LTS Linux distributions shipped with a Python-2 version which users can rely upon instead of the Python-3 version.

For Python-2, the default is for modules to run on Python-2.4.
This allows users with older distributions that are stuck on Python-2.4 to manage their machines.
Modules are allowed to drop support for Python-2.4 when one of their dependent libraries requires a higher version of Python.
This is not an invitation to add unnecessary dependent libraries in order to force your module to be usable only with a newer version of Python.; instead it is an acknowledgment that some libraries (for instance, boto3 and docker-py) will only function with a newer version of Python.

The only long term supported distro that we know of with Python-2.4 support is RHEL5 (and its rebuilds like CentOS5), which is supported until April of 2017.
For Ansible, that means Ansible-2.3 will be the last major release that supports Python-2.4 for modules. Ansible-2.4 will require Python-2.6 or greater for modules.
Cut Off date for Ansible-2.3 submissions has passed (Feb 15 2017) -->

- [ ] Python-2.4 or greater support
- [ ] Python-2.6 or greater support
- [ ] Python-3.5 or greater support

## Anything else?
If you'd like to add anything else beyond the above required and optional sections, you are welcome to do so.
