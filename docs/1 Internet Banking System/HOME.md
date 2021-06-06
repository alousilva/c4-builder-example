# 1 Internet Banking System

![diagram](https://www.plantuml.com/plantuml/svg/0/fLJ1JXin4BqZyGzJ3csGGa9HfKez0I4g808H6mezHRFUIUBMQwziRq9KzTyxzcQN3Kt5eJbivF7pl3VFCpvr7gqlSxM_zm7UIIrKcH4il2_SbtxVugetbtvHfgKZAupsf7rFcBoFcPMebweiolxWqz5OeVOFevl-nzx9ySbnx-DdZau7V02b9jih8aEJN-7QbDxjmkpltPnzltkOJ1-l9fVJc-7NuUr5vp34nsITqPqY5Lqug1Qeu1prJwddC2YTDpdP0zuy0x5PWPc1Nn2aZEh2Yak1eZuPOe12c59xrpjWZcJjFENJuRFlaECymwCSfG8Nmo7nX5D9Di66yoCfh75cvc7uB1QevmJKFl0wPPw6d2CkTcOnfqPvqgHFlB7a09MgTGiEHA41o0UDpT5Bem5JDh0fanFNXNJ1MzGEHO3nYhne2pbdK8PstP5HpLKiXdmjvk0GVktl0V-QU-cia86FbC9PKIWf8dzG-mEN2AWpI0eRv8s-3KBuWfHSigIedxlBIm6RpebettZ8j7LfZZ-Ae40s4Lzeel9jDQu8Sf8AFmxu7RASiBAewFXUIeMnBSRMB6MsCNYdZ5cfes-ef5-3Doy6mr9YE2CjhDYAr9eLJyGEVNcGDpAfL55Pu7t27DcXRGcWP2uzPU3ArB44u_z3KbxnRVuoMaf1ExHbQRWVz9YYeo3ddXHMoQ4EGo8Mb6Eh7SFeWwMvTDnPiVbQZTY51Re5bu4bIz5-Sn4WB6LXYQhgJN8Eb9ct6d9R6XOo3ExuwjzTvjjTrXZvXc718uJhvEwsVpcPZ84P8dl5p_LNp77S4zAPsyomYmQC9kDQQWEjnlZ1KOGyyPiN4YT_uQBPzuISyZsiBDyrZuG9PwulpWTjU1YmggthsMdlnftAdfgqAMUBDNy3zpjK7O3n1OrJNGCRJBDTwOdxxN3-EXgCgrxaBVT2fOmuvLXyrVy0)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.