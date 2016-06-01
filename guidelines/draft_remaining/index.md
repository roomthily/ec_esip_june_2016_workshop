---
layout: guidelines
---

# Draft Software Assessment Guidelines - Remaining Categories #

<div class="guidelines g-border">
    <h3>Table of Contents</h3>
    <div class="leftie">
        <ul>
            <li><a href="#fitness">Fitness</a>
                <ul>
                    <li><a href="#fitness-accuracy">Accuracy</a></li>
                    <li><a href="#fitness-credibilty">Credibility</a></li>
                </ul>
            </li>
            <li><a href="#sustainability">Sustainability &amp; Maintenance</a>
                <ul>
                    <li><a href="#sustainability-copyright">Copyright</a></li>
                    <li><a href="#sustainability-accessibility">Accessibility</a></li>
                    <li><a href="#sustainability-identity">Identity</a></li>
                    <li><a href="#sustainability-licensing">Licensing</a></li>
                    <li><a href="#sustainability-portability">Portability</a></li>
                    <li><a href="#sustainability-supportability">Supportability</a></li>
                </ul>
            </li>
        </ul>
    </div>
    <div class="leftie">
        <ul>
            <li><a href="#usabilty">Usability</a>
                <ul>
                    <li><a href="#usability-friendliness">Friendliness</a></li>
                    <li><a href="#usability-installability">Installability</a></li>
                    <li><a href="#usability-learnability">Learnability</a></li>
                    <li><a href="#usability-understandability">Understandability</a></li>
                </ul>
            </li>
            <li><a href="#other">Other</a>
                <ul>
                    <li><a href="#other-preservation">Preservation &amp; Archiving</a></li>
                    <li><a href="#other-credit">Credit</a></li>
                    <li><a href="#other-notebooks">Notebooks</a></li>
                </ul>
            </li>
        </ul>
    </div>
</div>

<div class="guidelines">
    <h3>About the layout</h3>
    <p>The layout used in the draft is meant to provide the first iteration of feedback for comment. </p>

    <div class="g-border">
        <div class="leftie">
            <h4>Criteria Options</h4>
            <div class="revisions">
                <div class="criterion">
                    <p class="original">The original statement.</p>
                    <p class="original questioned"><i class="fa fa-warning fa-fw"></i>The original statement, flagged for review.</p>
                    <p class="revision"><i class="fa fa-pencil fa-fw"></i>Suggested revisions to the original statement or a replacement for the original. The original statement is provided for reference.</p>
                    <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Suggested new statement.</p>
                    <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>Suggested revision is to delete the statement entirely.</p>
                </div>
            </div>
        </div>
        <div class="leftie">
            <h4>Criteria Descriptors</h4>
            <p>The descriptors provide additional context for the criterion if applicable.</p>
            <p><span>Application:</span> indicates whether a statement refers to only the codebase, the project as a whole (generally relates to project artifacts not part of the codebase such as a project website), or applies to both.</p>
            <p><span>Grouping:</span> describes a logical grouping to the criteria within a subcategory.</p>
            <p><span>Notes:</span> any notes provided by he initial reviewers regarding suggested revisions.</p>
            <p><span>References:</span> link to a citation providing a rationale for the criterion.</p>
            <p><span>Similar Criteria:</span> links to criteria listed in other subcategories that may be duplicated concepts.</p>
        </div>
    </div>

    <h2 id="fitness">Fitness</h2>
    <h3 id="fitness-accuracy">Accuracy</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">Tests exist to evaluate whether the results match the specification.</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Algorithm | Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">The precision presented in answers to the user is appropriate for the product's algorithm and implementation.</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Algorithm | Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">The product produces the same results in response to the same inputs (unless specification calls for randomness).</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Algorithm | Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">The product results are unaffected by increasing levels of use, analyzed inputs, or generated outputs; consistent with likely future demand.</p>
            </div>
            <div class="metadata">
               <h4>Application</h4>
                <p>Algorithm | Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">The specific results provided by the product match what the specification calls for.</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Algorithm | Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">There are examples of outputs that follow the specification.</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Algorithm | Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">There is a specification of the algorithm against which results can be compared.</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Algorithm | Code</p>
            </div>
        </div>
    </div> <!-- end Fitness: Accuracy -->

    <h3 id="fitness-credibility">Credibility</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">All web interfaces use secure (https) protocol</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Unclear application - project website or web application (the project's deliverable) in which case, is it better placed under Security?</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Any group access privileges or functions are supported through group membership, not through group login via a single account.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Auth and Access</p>
                <h4>Notes</h4>
                <p>Move to Security? Update to better reflect roles, groups, etc, terminology.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Expertise of the originators of the project/product is represented throughout the content as appropriate (e.g., in author pages, references, citations, and about or background pages).</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Opinions and perspectives are offered only as they relate to the mission of the project, and are clearly identified and put into context.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Presented information and data are consistent throughout the project.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Re-authentication (e.g., on lost password) requires appropriate verification (e.g., email to known account, or 2-factor authentication; not security questions).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Auth and Access</p>
                <h4>Notes</h4>
                <p>Move to Security? Wordsmith a bit?</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">The product user experience (e.g, response times) is materially unaffected by increasing levels of use, analyzed inputs, or generated outputs; consistent with user expectations.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">User can access all appropriate capabilities and information, but can not access any content or feature that should be privileged.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Auth and Access</p>
                <h4>Notes</h4>
                <p>Move to Security? Add statement re: testing the roles, etc. Possibly consideration some statement on 3rd party integrations?</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Where registration is allowed, registration validation is consistent with required project security (e.g., simple captcha for insecure public-facing resources; email required for mildly resource-constrained software; manual identity verification for critical products)</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Auth and Access</p>
                <h4>Notes</h4>
                <p>Move to Security? wordsmith, at least.</p>
            </div>
        </div> 
    </div> <!-- end Fitness: Credibility -->

    <h2 id="sustainability">Sustainability and Maintenance</h2>
    <h3 id="sustainability-copyright">Copyright</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">Each source code file/web page/document has a copyright statement.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">If supported by the language, each source code file has a copyright statement embedded within a constant.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">If there are multiple web sites then these all state exactly the same copyright, licencing and authorship.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site states copyright.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site states key roles: who developed/develops the product, funds it, oversees the web site, etc.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
    </div> <!-- end Sustainability:Copyright-->

    <h3 id="sustainability-accessibility">Accessibility</h3>
    <p>Ed. note: suggest revisions for three situations - 1) project members are hosting their own repository management system (git, Trac, etc) which does affect public/private access and browsability; 2) project members are using a third party DVCS like GitHub or BitBucket which affects public/private but other aspects are not directly tied to the *project* assessment; c) project members post their software repositories to a domain/research code system which is more related to publication and preservation (but still about whether the code is accessible).</p>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Ability to browse source code repository online.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Source Code</p>
                <h4>Notes</h4>
                <p>Realistically, could assume when hosting in external platform, ie GitHub, that this is a feature of the external system and not something to evaluate for the project itself.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Access to source code repository is available (whether for free, payment, registration).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Source Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Anonymous read-only access to source code repository.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Source Code</p>
                <h4>Notes</h4>
                <p>If kept, clarify language. The related flagged items read more as guidance to choose an external platform </p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Repository is hosted externally to a single organisation/institution in a sustainable third-party repository (e.g. SourceForge, GoogleCode, LaunchPad, GitHub) which will live beyond the lifetime of any current funding line.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>All repositories developed by the project team are hosted externally in a sustainable thrid-party platform, either a code-hosting platform or a domain- or research-specific software repository.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Source Code</p>
                <h4>Notes</h4>
                <p>Removing the platform names (too many are gone now) and including text for the newer domain area repositories (see Astronomy community efforts and some general research software repositories (OntoSoft)).</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source distributions are available (whether for free, payment, registration).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Source Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source distributions are available without the need for any registration or authorisation of access by the project.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Source Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source distributions are freely available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Source Code</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Binary distributions are available (whether for free, payment, registration).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Artifacts</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Binary distributions are available without the need for any registration or authorisation of access by the project.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Artifacts</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Binary distributions are freely available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Artifacts</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Downloads/versions page shows evidence of regular releases (e.g. six monthly, bi-weekly, etc.).</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>This seems out of place. Capture release scheduling under the larger Versioning umbrella. *If* releases needs to be under Accessibility, it needs to relate directly to the avaialability of the source code versions and the build artifacts.</p>
            </div>
        </div>
    </div> <!-- end Sustainability: Accessibility -->

    <h3 id="sustainability-identity">Identity</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project/product/software has a distinct name regardless of its application area. A search by Google on the name plus keywords from the application area throws up the project web site in the first page of matches.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Project/software name or acronym is distinct within the application area.</p>
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project/software name or acronym is easily discoverable, eg. the acronym is not a very common word or, if it is, the phrase provides additional information for discovery.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Branding</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project/product/software has a distinct name within its application area. A search by Google on the name plus keywords from the application area throws up the project web site in the first page of matches.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Branding</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project/product/software has a logo.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Branding</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project/product/software has its own domain name.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Basic</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>Project/product/software name does not throw up embarrassing “did you mean…” hits on Google.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Maybe should just be a better guideline on naming? Three is a lot related to search?</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project/product/software name does not violate an existing trade-mark.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Basic</p>
                <h4>Notes</h4>
                <p></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project/product/software name is trade-marked.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Advanced</p>
            </div>
        </div>
    </div> <!-- end Sustainability:Identity -->

    <h3 id="sustainability-licensing">Licensing</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>Each source code file or document has a licence header; each web page has a rights and authorship footer.</p>
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>License is specified in each source code file or document.</p>
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project website includes authorship information.</p>
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Each code repository README (or similar) indicates license applied.</p>
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Each code repository README (or similar) includes authorship information.</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Both</p>
                <h4>Notes</h4>
                <p>Many concepts in the original (need to check for duplication across criteria).</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Site or product content has a 'free for public use' license or statement.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Project website has a 'free for public use' license or statement.</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Project</p>
                <h4>Notes</h4>
                <p>Consistent language ("project website").</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Site or product content has a license.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Project website has a license.</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Project</p>
                <h4>Notes</h4>
                <p>Consistent language ("project website").</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Software (source and binaries) has a licence.</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Software has an Open Software Initiative (OSI) recognised licence.</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Software has an open source licence.</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site states applicable licences.</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Project</p>
            </div>
        </div>

        <!-- scott -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project documentation defines contributor license agreements, either by requesting a CLA or by stating the rights transferred to the project by a contributor not directly affiliated with the project.</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Code</p>
            </div>
        </div>
    </div> <!-- end Sustainability:Licensing -->

    <h3 id="sustainability-portability">Portability</h3>
    <p>Ed. note: this entire section is flagged for review, to be resolved by either condensing the two main concepts (software can be built and run on multiple platforms and web application functions across multiple browsers) into more general criteria or by removing the section altogether and updating related criteria in other sections (such as buildability and documentation criteria related to that).</p>
    <div class="criteria">
        <!-- gallagher -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>For code that compiles and does not use a VM: Uses a build system that interogates the build environment to determine features AND the software actually uses the result of that interogation</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Software</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>For code that is interpreted: Follows standard (likely ad hoc) practices for distribution and interpreter version/selection.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Software</p>
            </div>
        </div>

        <!-- elliott -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>If the algorithm takes advantage of GPU architecture, is it hardware vendor agnostic?</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>GPU/Hardware</p>
                <h4>Notes</h4>
                <p>If the code takes advantage a GPU for its computation, does it use a vendor specific language (e.g. CUDA), or an open standard capabile of running on multiple hardware platforms (e.g OpenCL)?  Using an open standard helps to ensure that more users can run it on their existing systems.  In addition, open standards will likely help with maintainability and compatibility down the road.  CUDA requires NVIDIA cards, whereas OpenCL can run on NVIDIA, AMD, and Intel graphics cards.</p>
            </div>
        </div>

        <!-- scott -->
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Application can be built on and run under Debian.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Application can be built on and run under Fedora.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Application can be built on and run under MacOSX.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Application can be built on and run under RedHat.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Application can be built on and run under Solaris.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Application can be built on and run under Ubuntu.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Application can be built on and run under UNIX/Linux.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Application can be built on and run under Windows 7.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Application can be built on and run under Windows Vista.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Application can be built on and run under Windows XP.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Application can be built on and run under Windows.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Browser applications/sites run under Google Chrome.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Browser applications/sites run under Internet Explorer.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Browser applications/sites run under Mozilla Firefox.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Browser applications/sites run under Opera.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Browser applications/sites run under Safari.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
    </div> <!-- end Sustainability:Portability-->

    <h3 id="sustainability-supportability">Supportability</h3>
    <p>Ed. note: criteria marked as <code>Grouping: Email</code> need revision for the different modes of email support and regrouped accordingly (direct email, form-based contact, mailing list). </p>
    <div class="criteria">
        <!-- scott -->
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Above pages/windows/files describe, or link to, a description of “how to ask for help” e.g. cite version number, send transcript, error logs etc.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Not sure about "Above" here. Maybe meant to be "About"? Seems to describe an email/contact page template for help requests.</p>
            </div>
        </div>

        <!-- emails -->
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project has an e-mail address.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Project has an e-mail address for support.</p>
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project website includes a contact form for requesting support.</p>
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project provides a mailing list for requesting support.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Email</p>
                <h4>Notes</h4>
                <p>Needs a switch statement - email for support, contact form for support, mailing list, irc, bug tracking system? Sort of conflates "email address" with mailing list functionality.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project e-mail address has project domain name.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Project e-mail uses the project's domain name.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Email</p>
                <h4>Notes</h4>
                <p>Not sure these kinds of statements are broadly applicable - it assumes more of an OS model but university or research/science code out of federal agencies may not be able to use a project domain.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">E-mail archives are publicly readable.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Email</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">E-mail archives are searchable.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Email</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">E-mail lists or forums, if present, have regular posts.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Email</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">E-mails are archived.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Email</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>E-mail archives or ticketing system shows that queries are responded to within a week (not necessarily fixed, but at least looked at and a decision taken as to their priority).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Email</p>
                <h4>Notes</h4>
                <p>Flagged - not a marker that is actionable by a project member (consider shift to project analytics assessment section).</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>E-mails are read by more than one person.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Email</p>
                <h4>Notes</h4>
                <p>Is this evaluatable by an external evaluator?</p>
            </div>
        </div>


        <div class="criterion">
            <div class="revisions">
                <p class="original">If there is a blog, is it is regularly used.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project resources are hosted externally to a single-organisation/institution in a sustainable third-party repository (e.g. SourceForge, GoogleCode, LaunchPad, GitHub) which will live beyond the lifetime of the current project.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Project resources are hosted externally to a single-organisation/institution in a sustainable third-party repository, such as GitHub, or a research software repository which will live beyond the lifetime of the current project.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>"third-party repository" does not describe GH or the others well. And a bit about domain-specific or research software-specific repositories as archive locations.</p>
            </div>
        </div>
        
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project has a ticketing system.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Issues</p>
                <h4>Notes</h4>
                <p></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Ticketing system is publicly readable.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Issues</p>
                <h4>Notes</h4>
                <p></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Ticketing system is searchable.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Issues</p>
                <h4>Notes</h4>
                <p></p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>Software describes how to get support (in a README for command-line tools or a Help=>About window in a GUI).</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Source code repository, in a README or similar document, describes how to get support.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Software, as built application, includes how to get support through a Help window or other common interface feature.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Support pointers</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">User doc has page describing how to get support.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Support pointers</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has page describing how to get support.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Support pointers</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Web site has search facility.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Flagged - can we come up with a reason related to project maturity for this criterion?</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Web site has site map or index.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Flagged - can we come up with a reason related to project maturity for this criterion?</p>
            </div>
        </div>
    </div> <!-- end Sustainability:Supportability-->

    <h3 id="usability-friendliness">Friendliness</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">All essential options and information for a task are visible, while excess information is avoided. Display elements are easily distinguished, and tool tips provided. Possible and impossible actions are indicated.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Display handles variety of scales, including mobile phone size if that is targeted, while allowing user ready access to needed controls.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>The web application was developed using responsive design principles.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Here referring to the application developed as the code/software deliverable and not a project website. But it also applies to the project website.</p>
                <h4>References</h4>
                <p><a href="#"></a>[ADD: ref to responsive design http://alistapart.com/article/responsive-web-design]</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Generated data products are organized clearly, with embedded metadata wherever possible.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Generated data products are organized clearly, with associated metadata clearly identifiable.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Step 1: data + metadata.</p>
            </div>
        </div>
        <!-- scott -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Generated data products and their related metadata are provided in data packages and those data packages are organized clearly.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Step 2: data packages.</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Lists of resources are neatly presented for easy access, comparison, access to details, and handling of scale. Both filter and scrolling are available; user can control number of items presented.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Unclear what this refers to unless it's a ToC or file browser pane? If yes, needs clearer wording.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Simple and common tasks are easy to perform and communicated clearly and simply in the user's reference frame. The product minimizes the effort for users, by making appropriate assumptions, presenting appropriate defaults, and offering appropriate short-cuts.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>System can be controlled or used by foreign speakers and color-vision-deficient individuals.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Two concepts in the original - localization and accessibility. Splitting into clearer criteria (language may not be high priority for projects (localization is hard) but accessibility (beyond color-blindness) is more than doable with clean markup, etc.</p>
            </div>
        </div>

        <!-- scott -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project web site provides localization options, ie support for non-English speakers.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Localization/Internationalization. Open question re: is localization tied to project goals or more generally (reqs from funder, etc) given that it is not always a straightforward task? Applies to Identity, Documentation and other Usability categories.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project web site follows established guidelines for web accessibility. </p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Accessibility</p>
                <h4>References</h4>
                <p><a href="#"></a>https://www.w3.org/standards/webdesign/accessibility, WCAG, Section 508</p>\
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Web application follows established guidelines for web accessibility whenever possible.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Accessibility. Note limitations in mapping frameworks which may result in accessibility being tied to color-blind friendly color scheme.</p>
                <h4>References</h4>
                <p><a href="#"></a>https://www.w3.org/standards/webdesign/accessibility</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Terminology used throughout the system or product is internally consistent, appropriate to the context, and suitable for targeted users, avoiding codes unless universally known.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">User commands are quickly and intuitively reflected in system behavior and subsequent system presentation (e.g., previous filters remain visible).</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">User intefaces maintain consistent patterns of behavior and style (e.g., buttons and cancel/save exits have consistent look and feel), creating an understandable presentation throughout the application.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">User interfaces are organized in meaningful and useful ways that are recognizable to users.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">User mistakes are tolerated gracefully; multiple levels of "command undo" are provided, paths to 'go back' are available, irreversible actions are rare but verified if needed, and suggestions are offered in response to faulty input.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">User variation is handled automatically; varying sequences and input formats are handled, and reasonable actions are accepted.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Users are informed of relevant software actions, state changes, errors, and assumptions in clear and simple ways.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
    </div> <!-- end Usability:Friendliness -->

    <h3 id="usability-learnability">Learnability</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">A getting started guide is provided outlining a basic example of using the product.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">API documentation is provided for userdevelopers and developers.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>API documentation is provided for user-developers and developers.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Instructions are provided for many basic use cases.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Instructions are provided supporting all use cases.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Reference guides or contextual specifications (may be simple labels, if clear) are provided for all command line, GUI and configuration options.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
    </div> <!-- end Usability:Learnability-->

    <h3 id="usability-understandability">Understandability</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">Architectural overview, with diagrams, is available.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Architectural overview, with diagrams, is included or referenced in the documentation.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Case studies of use are available.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Case studies of use are included or referenced in the documentation.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Descriptions of intended use cases are available.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Descriptions of intended use cases are included or referenced in the documentation.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Design rationale is available – why the system does things the way it does.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Design rationale is included or referenced in the documentation – why the system does things the way it does.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">High-level description of how the product works is available.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>High-level description of how the product works is included or referenced in the documentation.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">High-level description of what the product does is available.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>High-level description of what the product does is included or referenced in the documentation.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">High-level description of what/who the product is for is available.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>High-level description of what/who the product is for is included or referenced in the documentation.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Constraints or restrictions are archived with the source code.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Constraints or restrictions are included or referenced in the documentation and archived with the source code.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
    </div> <!-- end Usability:Understandability -->

    <h3 id="other-preservation">Preservation/Archiving</h3>
    <div class="criteria">
        <!-- downs -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Source code used to create data are archived with the data or separately with bidirectional references between the data and software.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Source code developed for accessing or using the data are archived with the data or separately with bidirectional references between the data and software.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Documentation are archived with the source code.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Licenses are archived with the source code.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Constraints or restrictions are archived with the source code.</p>
            </div>
            <div class="metadata">
            </div>
        </div>

        <!-- toner -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Document describing known environment in which code was originally run</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>List known dependencies</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>consider container technologies to ensure reproducibility of software content or function.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>documentation describing objectives of software, known limitations or bugs, and reason for and purpose of its existence</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Ideally, preserved/archived code should include "test data", so future users can unpack and run code, and see if results appear as expected. (Unless data is already archived elsewhere)</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Code should be documented in a natural language explaining each process/code section.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>(In some cases, preserving code for reuse is impossible, but being able to refer back to old code and follow it without needing to know intimately the language it was written in is helpful.)</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Archived code should not be an executable (.exe) but a group of files packaged together that can be built or reviewed by future users for understanding. Code should be as self-contained as possible.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Does the software use open source platforms and libraries, or does it require the use of licensed software?</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Copyright/licensing must be noted and made clear to future users. </p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Archived code should include any documentation that applies to the particular release of the code--including both specific version documentation and overall software documentation. </p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>(Resources enabling "usability" of code also apply to future users acquiring code from the archive.)</p>
            </div>
        </div>
    </div> <!-- end Preservation -->

    <h3 id="other-credit">Publication &amp; Credit</h3>
    <div class="criteria">
        <!-- downs -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Authors of software are identified in the suggested citation for the software.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Substantial contributions to software are considered authorship.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Other contributions to software are acknowledged in documentation.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Authors of documentation are identified in the suggested citation for the documentation.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Software used to create data are cited in the data documentation.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Data for which the software were created are cited in the software documentation.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Review committees consider and recognize software contributions and citations of software.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Publications about the data cite the software used to create the data.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Publications about the use of the data cite the software used to analyze the data.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
    </div> <!-- end Credit -->

    <h3 id="other-notebooks">Notebooks</h3>
    <div class="criteria">
        <p>Ed. note: Suggested new category given the popularity of Jupyter/iPython Notebooks (or similar systems) in research settings.</p>
    </div>
</div>