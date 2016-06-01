---
layout: guidelines
---

# Draft Software Assessment Guidelines - Priority Categories #

<div class="feedback">
    <p>We ask that you consider a few things when looking over these guidelines.</p>
    <ol>
        <li>Is the statement evaluatable by someone external to the project? When reading the criterion, can you think of some feature common to code files, code repositories, documentation, or a project website you would look for? If not, do you consider the concept referenced in the statement to still be important to code or project quality? </li>
        <li>Does the criterion's concept reflect an ideal endpoint? Can you suggest meaningful and evaluatable criteria that are actionable community practices that lead to that ideal (and are those reflected in other criteria here)? What is the happy path?</li>
        <li>Is the criterion (or the group) related to active development efforts or to preservation/maintenance efforts? Consider a research project lifecycle.</li>
        <li>Is the criterion or group associated with a codebase or the project information? Does it relate to code maturity or project maturity and is that clear from the statement?</li>
        <li>For any criteria directly related to code, can the criterion be applied to any codebase or software artifact or does it apply only to one (or a few) types of software, such as a plugin/extension, module/library, web application, web service, desktop application, etc?</li>
        <li>Is the criterion *directly* related to the software/code developed for the project, eg is it the deliverable? The aim is to not assess the framework used, for example, but the plugin or customizations made explicitly for the project.</li>
    </ol>
    <p>Finally, consider the criteria in relation to a project or codebase you're familiar with. </p>
</div>

<div class="guidelines g-border">
    <h3>Table of Contents*</h3>
    <div class="leftie">
        <ul>
            <li><a href="#sustainability">Sustainability &amp; Maintenance</a>
                <ul>
                    <li><a href="#sustainability-analysability">Analysability</a></li>
                    <li><a href="#sustainability-changeability">Changeability</a></li>
                    <li><a href="#sustainability-community">Community</a></li>
                    <li><a href="#sustainability-evolvability">Evolvability</a></li>
                    <li><a href="#sustainability-governance">Governance</a></li>
                    <li><a href="#sustainability-interoperability">Interoperability</a></li>
                    <li><a href="#sustainability-testability">Testability</a></li>
                </ul>
            </li>
        </ul>
    </div>
    <div class="leftie">
        <ul>
            <li><a href="#usabilty">Usability</a>
                <ul>
                    <li><a href="#usability-buildability">Buildability</a></li>
                    <li><a href="#usability-documentation">Documentation</a></li>
                    <li><a href="#usability-installability">Installability</a></li>
                </ul>
            </li>
            <li><a href="#other">Other</a>
                <ul>
                    <li><a href="#other-security">Security</a></li>
                    <li><a href="#other-performance">Performance</a></li>
                </ul>
            </li>
        </ul>
    </div>
</div>

<p>* The categories listed here contain most of the current revisions related to priorities laid out before the workshop. </p>

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
    
    <h3 id="sustainability-analysability">Analysability</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source code is commented.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Clean Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source code is laid out and indented well.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Clean Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source code or content is structured into modules or packages.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Clean Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source code uses sensible class, package and variable names.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Clean Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">There are no TODOs in the code.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Clean Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">There is no commented out code.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Clean Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">There are no old source code files that should be handled by version control e.g. “SomeComponentOld.java”.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Clean Code</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Coding standards are recommended by the project.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Coding standards, for each programming language used, are recommended by the project.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Standardized Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Coding standards are required to be observed.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Standardized Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project-specific coding standards are consistent with community or generic coding standards (e.g. for C, Java, FORTRAN, Python, Ruby, etc.)</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Standardized Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Coding standards are verified using a linter (should one be available for the given programming language).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Standardized Code</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Styleguides are provided for the project.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Standardized Code</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Source code comments are written in an API document generation mark-up language e.g. JavaDoc or Doxygen.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Document Generation</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project documentation identifies the API generation tool used.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Document Generation</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project documentation describes how to regenerate the documentation</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Document Generation</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project uses automated documentation generation tool, e.g. Swagger or RAML.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Document Generation</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Source code or content repository is a revision control system.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Source code or content repository is managed through a version control system.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source or content releases are snapshots of the repository.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Releases follow protocols of the version control system in place.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Tagged Git releases, etc.</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>Auto-generated source code is in separate directories from other source code.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Revisit depending on portability/buildability revisions</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>How to regenerate the auto-generated source code is documented.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Revisit depending on portability/buildability revisions</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>Project files for IDEs are provided.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Revisit depending on portability/buildability revisions</p>
            </div>
        </div>
    
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source code structure relates clearly to the architecture or design.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        
        <div class="criterion">
            <div class="revisions">
                <p class="original">Structure of the source code or content repository and how this maps to the software’s components is documented.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
    </div> <!-- end Sustainability:Analysability-->

    <h3 id="sustainability-changeability">Changeability</h3>
    <div class="criteria">
        <!-- scott -->
        <div class="criterion">
            <div class="revisions">
                <p class="original">Changes in the source code repository are e-mailed to a mailing list.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Changes to the source code repository are made available through some notification system, whether mailing list of ticketing system notifications.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Dev Transparency</p>
                <h4>Notes</h4>
                <p>Updated to reflect GitHub/BitBucket/Trac interactions ("watch" functionality).</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">This e-mailing list can be subscribed to by anyone.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Anyone can subscribe to the notification system providing software release updates.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Dev Transparency</p>
                <h4>Notes</h4>
                <p>Check for duplication in the ticketing system criteria.</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Contributions policy is publicly available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Contribution Policy</p>
                <h4>Notes</h4>
                <p>See also Governance (and shift to governance? to match FLOSS organizational conversations?)</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Contributors retain copyright/IP of their contributions.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Contribution Policy</p>
                <h4>Notes</h4>
                <p>If we're following the open source model, this is incorrect - Contributor License Agreements release the rights from the contributor back to the project. The original implies that someone could revoke permissions for their contribution to a project, which would have credibility/stability issues. </p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project has defined a contributions policy.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Contribution Policy</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Users, user-developers and developers who are not project members can contribute.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Contribution policy is not limited to code contributions and describes processes for anyone to contribute to the project even if nt project members.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Contribution policy</p>
                <h4>Notes</h4>
                <p>(Not policy but maybe there should be a stronger section under community for explicitly stating non-project member options or under governance or is it implied by having a CONTRIBUTING statement?)</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Project has defined a stability/deprecation policy for components, APIs, pages, etc.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Change policies</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>Releases document deprecated components/APIs in that release.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Change policies</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>Releases document removed/changed components/APIs in that release.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Change policies</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>A release is accompanied by a change log document (or update to a CHANGELOG document), including deprecated or modified components/APIs.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Change policies</p>
                <h4>Notes</h4>
                <p>Merged the previous into one statement about change logs.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Stability/deprecation policy is publicly available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Change policies</p>
            </div>
        </div>

        <!-- scott -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Source code uses semantic versioning for major and minor releases.</p>
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Contribution policy indicates project's versioning method.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Versioning</p>
                <h4>Notes</h4>
                <p>Related to releases, software artifacts, and milestones. </p>
            </div>
        </div>
    </div> <!-- end Sustainability:Changeability-->
    

    <h3 id="sustainability-community">Community</h3>
    <div class="criteria">
        <!-- scott -->
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Users are requested to cite the product if publishing papers based on results derived from the product.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Flagged for publication/credit binning</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Users are required to cite a boilerplate citation if publishing papers based on results derived from the product.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Flagged for publication/credit binning</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has list of important partners and collaborators.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Project in the wild</p>
                <h4>Notes</h4>
                <p>(Applies to any "Project in the wild") This hits project lifecycle concerns (most of these criteria are unlikely to be true for a project on its first grant round) so need to clarify *when* we expect to see these kinds of features. Also gets to Identity (esp. the parts tied to branding) and post-publication concerns which don't speak to community. Consider community around developing/actively using codebase and scholarly community as different criteria buckets?</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has list of software that uses/bundles this product, or sites that reference this work.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Project in the wild</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has list of the project’s publications.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Project in the wild</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has list of third-party publications that cite the product.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Project in the wild</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has quotes from satisfied users.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Project in the wild</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has statement of number of users/developers/members.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Project in the wild</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has success stories.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Project in the wild</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Developers exist who are not members of the project.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Users exist who are not members of the project.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
    </div> <!-- end Sustainability:Community -->

    <h3 id="sustainability-evolvability">Evolvability</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site describes end dates of current funding lines.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Funding/Sustainability</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site describes how project is funded/sustained.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Funding/Sustainability</p>
            </div>
        </div>
        
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site describes project roadmap or plans or milestones (either on a web page or within a ticketing system).</p>
            </div>
            <div class="metadata">
            </div>
        </div>

        <!-- kokkonen -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Web site describes software requirements on hardware, operating system versions, tool versions.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>(Check documentation for OS, 3rd party versions; wherever it winds up, a group for Hardware is a good idea (GPU-optimized code, etc)</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Software includes no arbitrary shutdown dates.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Consider a more general statement against global defaults or hard-coded defaults in the code base (we can provide examples of similar issues around default size limits, etc. Guidelines - limited use of globals, uses configuration files.</p>
            </div>
        </div>

        <!-- scott -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>[Ed. note: some criteria related to reuse of OS frameworks, ie. not reinventing every wheel. This is a placeholder and reminder.]</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Reuse</p>
            </div>
        </div>
    </div> <!-- end Sustainability:Evolvability-->

    <h3 id="sustainability-governance">Governance</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project has defined a governance policy.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Governance policy is publicly available.</p>
            </div>
            <div class="metadata">
            </div>
        </div>

        <!-- scott -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project website or code repository contains documentation describing the contribution policies and procedures.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Contribution</p>
                <h4>Notes</h4>
                <p>Probably a repeated concept but currently comes up in FLOSS governance discussions, might just need to be shifted from various other sub-categories.</p>
                <h4>References</h4>
                <p><a href="#"></a>See "contributing Guidelines" ref.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Contribution policies and procedures included in a CONTRIBUTING file.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Contribution</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Contribution policies and procedures describes the code review process, including who performs the review, who accepts the reviews and how long reviews take.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Contribution</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Contribution policies and procedures clearly define decision making processes for all contributors.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Contribution</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project website or code repository includes a code of conduct.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
    </div> <!-- end Sustainability:Governance -->

    <h3 id="sustainability-interoperability">Interoperability</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">Provides tests demonstrating compliance to open standards.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Uses mature, ratified, non-draft open standards.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Uses open standards.</p>
            </div>
            <div class="metadata">
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>[Placeholder - implements JSON-LD, etc.]</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Noted need for service/API interoperability criteria.</p>
            </div>
        </div>
    </div> <!-- end Sustainability:Interoperability -->

    <h3 id="sustainability-testability">Testability</h3>
    <p>Suggested category grouping: project has unit and integration tests (1); tests are run by a continuous integration (CI) system once committed (2). Include coding standards and autoomated coverage analysis as (3) but less crucial than testing and CI. Reconsider criteria that are commonly provided by a CI system and whether those are suggested criteria on their own merit.</p>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">A minimum test coverage level that must be met has been defined.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Continuous integration is supported – tests are automatically run whenever the source code changes.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">For GUIs, project uses automated GUI test frameworks.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project has automated tests to check conformance to coding standards.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Project has Unit Tests where apropriate and they can be run automatically, including by a CI system.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>[SS] The original statement is ambiguous - does it refer to a coding standard such as PEP8 and is then testable with a linter or does it refer to unit testing, etc (as seen in the suggested revision)?</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>Project has automated tests to check test coverage.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Drop this. IMHO, it's far more important to have tests that are run automatically and by a CI system than to try for some % coverage. Classes that are 90% accessors don't need high coverage while classes that include complex/new algorithms do. </p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project has integration tests.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Project has integration tests and they can be run automatically, including by a CI system.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>[SS] For scaffolding, etc, consider splitting this out into two criteria but define the relationship.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project has scripts for testing scenarios that have not been automated (e.g. for testing GUIs).</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project has unit tests.</p>
            </div>
            <div class="metadata">
            </div>
        </div>

        <!-- kokkonen -->
        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>Project recommends tools to check conformance to coding standards.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>I don't see the value of a project *recommending* tools. Either code is being tested by its developers or it isn't. Perhaps if the software in question is itself a developer tool like a language, it should recommend testing tools, but that is a very special case that doesn't seem applicable here.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>Project recommends tools to check test coverage.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Maybe this applies for "Library/Module", but I would deprecate</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Project specifies how to set up external resources e.g. FTP servers, databases for tests.</p>
            </div>
            <div class="metadata">
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Test results are e-mailed to a mailing list.</p>
            </div>
            <div class="metadata">
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Test results are visible publicly.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Is this appropriate at all and if it is a common/recommended practice to deliver test results outside the development team.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Test results are visible to all developers/members.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Tests are automatically run nightly.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Is this kind of statement necessary with CI systems? And would a code repo have any signal to indicate this to an external evaluator?</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Tests create their configuration own files, database tables etc.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Tests create their own configuration files, database tables etc.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original deprecated"><i class="fa fa-trash fa-fw"></i>There is an automated test for this minimum test coverage level.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Given the other notes for test coverage, deprecate.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">This e-mailing list can be subscribed to by anyone.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>The test results e-mailing list can be subscribed to by anyone</p>
            </div>
            <div class="metadata">
            </div>
        </div>

        <!-- kokkonen -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project measures both conditional and line test coverage levels</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Conditional (branch) coverage is harder to achieve but just as important as line coverage</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Expected test results are based on verifiable criteria.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Just executing a line of code isn't worth much unless the results or side effects are compared to verifiable expected results</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Code is designed to support efficient testing.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>If code isn't designed with testing in mind, verifiable tests can be convoluted or impossible to write.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Tests use mocking technology where appropriate.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Mocking improves the focus, performance, and flexibility of unit tests. Most importantly it supports testing conditions that occur rarely or have perhaps never been observed so far.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Tests cover exceptional conditions as well as expected behavior.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>It's just as important to test for things that are unlikely to occur as for those that are part of nominal behavior.</p>
            </div>
        </div>

        <!-- scott -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Test suite includes tests to ensure correct permissions are maintained across the range of configurations.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>This is specifically for collaboration software but has been an issue in university-developed platforms (configuration options for permissions to a piece of content may result in unexpected access violations).</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>For software implementing third party integrations, those integrations are tested in the test suite.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>This is specifically for collaboration software.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>For software implementing third party integrations, the access needs of the integration for the software's stated purpose is clearly indicated to the user.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>This is specifically for collaboration software. (And is in the wrong category right now.)</p>
            </div>
        </div>
    </div> <!-- end Sustainability:Testability-->

    <h2 id="usability">Usability</h2>
    <h3 id="usability-buildability">Buildability</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">All mandatory third-party dependencies or external references are currently available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">All optional third-party dependencies or external references are currently available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">An automated build (e.g. Make, ANT, custom solution) is used to build any software.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>An automated build (e.g. Make, ANT, Maven, Gradle, or other language-specific build tool) is used to build any software.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Dependency management is used to automatically download dependencies (e.g. ANT, Ivy, Maven or custom solution).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>This is generally not an option for non-Java compiled code. However, there is a related idea for C and C++...</p>
                <!-- add note for things like python requirements.txt (pip, etc) and update language to refer more broadly to non-Java situations. -->
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source distributions have instructions for building corresponding software.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <!-- gallagher -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Code follows the GNU software guidlines and uses README, NEWS, INSTALL and COPYING files to describe the package (INSTALL includes the build information this case).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>related to previous statement.</p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <!-- end gallagher -->

        <div class="criterion">
            <div class="revisions">
                <p class="original">Source distributions list all third-party dependencies that are not bundled, along with web addresses, suitable versions, licences and whether these are mandatory or optional.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Tests are provided to verify the build or distribution has succeeded, or service/information is presented as intended.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has instructions for building the product.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site lists all third-party dependencies that are not bundled, along with web addresses, suitable versions, licences and whether these are mandatory or optional.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>

        <!-- gallagher -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Binary and source packages reference thrid-party code (including the acceptable versions) so that commonly-used tools (e.g., yum, apt-get) will automaticlly fetch those source/binary packages</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project uses build tools (e.g. automake, etc.) in a way that integrates with linux distro packager's expectations so they can/will build packages for public repos.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project supports common/standard (ad hoc) binary packaing tools (e.g., RPM, python egg). This means that a 'buildable' package provides binaries (or the equivalent) so that it can simply be installed and does not have to be built!</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p></p>
                <h4>References</h4>
                <p><a href="#"></a></p>
                <h4>Similar Criteria</h4>
                <p><a href="#"></a></p>
            </div>
        </div>

        <!-- kokkonen -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Build instructions include platform-dependent details and answers to frequently asked questions.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Build instructions include clear version requirements for external dependencies (unless automated dependency management is provided).</p>
            </div>
            <div class="metadata">
            </div>
        </div>
    </div> <!-- end Usability:Buildability -->

    <h3 id="usability-documentation">Documentation</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Code is documented (comment blocks, etc.)</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>API Docs</p>
                <h4>Notes</h4>
                <p>To allow present/future developers to be able to quickly understand and/or modify the software.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Pre/Post conditions are clearly defined</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>API Docs</p>
                <h4>Notes</h4>
                <p>To inform present/future developers of the expected input and output of the function.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Comment blocks are well-structured and consistent, following language or project standards.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>API Docs</p>
                <h4>Notes</h4>
                <p>Step before auto-generating where comments are clean and consistent across the project.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">API documentation is autogenerated (e.g., by JavaDoc or Doxygen), and documents APIs completely (e.g., configuration files, property names, etc.).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>API Docs</p>
                <h4>Notes</h4>
                <p></p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Does not use terms like “intuitive”, “user friendly”, “easy to use”, “simple” or “obviously”, unless as part of quotes from satisfied users.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Style</p>
                <h4>Notes</h4>
                <p></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">English language descriptions of commands and errors are provided but only to complement the above.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Style</p>
                <h4>Notes</h4>
                <p>Clearer to state that commands/errors have corresponding plain English descriptions in the docs?</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Plain-text files (e.g. READMEs) use indentation and underlining (e.g. === and ---) to structure the text, and avoid TAB character indentation.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Text files for higher-level documentation, such as README or CONTRIBUTING sections, use a common and identifiable markup language.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Repo Doc style</p>
                <h4>Notes</h4>
                <p>So markdown or reStructuredText but keeping it open to new "flavors".</p>
            </div>
        </div>


        <div class="criterion">
            <div class="revisions">
                <p class="original">Further information is suitable for the level of the reader, for each class of user.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Explanations should be free of jargon.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Audience</p>
                <h4>Notes</h4>
                <p>Users can have diverse experiences.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Partitioned into sections for users, user-developers and developers (depending on the software).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Audience</p>
                <h4>Notes</h4>
                <p></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>States assumed background and expertise of the reader, for each class of user.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Audience</p>
                <h4>Notes</h4>
                <p>This is often implied by the different kinds of documentation made available? Might be better to change to something that reflects "User Guide" or "Developer's Guide".</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Documentation is on the project web site.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>A link to the documentation is contained in the code.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Documentation is on the project website or the project website provides a clear link to an externally-hosted documentation web site.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Doc Management</p>
                <h4>Notes</h4>
                <p>Code and documentation can be separated.</p>
                <p>Consensus for documentation that is hosted by the project or that is hosted on some third-party site such as Read The Docs.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Documentation on the project web site makes it clear what version of the product the documentation applies to.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Doc Management</p>
                <h4>Notes</h4>
                <p></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Documentation is held under version control alongside any code or other product components.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Doc Management</p>
                <h4>Notes</h4>
                <p></p>
            </div>
        </div>
        <!-- gallagher -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Where available, project takes advantage of public-facing tools' documentation support. For example, github supports a README file that uses Markdown. It's pretty quick to write and is displayed automatically when a person goes to get the source. Maybe this has more to do with 'buildability,' but in some cases it might be all the documentation an initial author writes. </p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Doc management</p>
                <p><a href="#"></a></p>
            </div>
        </div>
        <!-- scott -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>The documentation for a specific software release is available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Doc management</p>
            </div>
        </div>
        
        
        <div class="criterion">
            <div class="revisions">
                <p class="original">Consists of clear, step-by-step instructions for use or adoption.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Content</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">For common problems and error messages, the symptoms and step-by-step solutions are provided.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Documentation is updated to reflect new errors and resolution methods identified.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Content</p>
                <h4>Notes</h4>
                <p>New errors and resolutions can be identified over time.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Gives examples of what the user can see at each step, e.g., screen shots or command-line excerpts; installation outcomes; working examples and error examples.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Content</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Lists resources for further information.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Content</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Provides a high-level overview of the product.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Content</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Constraints or restrictions are included in the documentation.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Content</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Quality control information is included in the documentation.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Content</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">States command names and syntax, says what menus to use, lists parameters and error messages exactly as they appear or should be typed; or provides similarly explicit instructions on how to apply product.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Code or GUI examples provided in the documentation reflect the current state of the software, ie. parameter names in the code match those found in the documentation.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Content</p>
                <h4>Notes</h4>
                <p>Rephrasing for clarity?</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Uses teletype-style fonts for command line inputs and outputs, source code fragments, function names, class names etc.; uses appropriately styled fonts for key information and special terms or links.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Documentation follows commmon styles for displaying code blocks.</p>
                <p class="revision added"><i class="fa fa-pencil fa-fw"></i>Documentation clearly distinguishses between input and output blocks.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>(Style?)</p>
                <h4>Notes</h4>
                <p>If nothing else, code blocks or inline snippets are rendered with monospaced fonts (which is the searchable term in most font browsers).</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>For software, a best-practice guideline is selected and code is validated against it.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>What does this mean? Do you mean -- For software, use industry best practices for a given language or platform and then validate that the code meets those practices (i.e., a third party code review).</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Is task-oriented or objective-oriented.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
                <h4>Notes</h4>
                <p>Not clear what this is referring to.</p>
            </div>
        </div>        
    </div> <!-- end Usability:Documentation-->

    <h3 id="usability-installability">Installability</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>All GUIs contain a Help menu with commands to see the project name, web site, how/where to get help, version, date, licence and copyright (or where to find this information), location of entry point into user doc.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Suggested move to a different sub-category</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site lists all third-party dependencies and external references that are not bundled, along with (as appropriate) web addresses, suitable versions, licences and whether these are mandatory or optional.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Dependencies</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">All mandatory third-party dependencies or external references are currently available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Dependencies</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">All optional third-party dependencies or external references are currently available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Dependencies</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Dependency management is used to automatically download dependencies (e.g. ANT, Ivy, Maven or custom solution).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Dependencies</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Binary distributions list all third-party dependencies and external references that are not bundled, along with (as appropriate) web addresses, suitable versions, licences and whether these are mandatory or optional.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Dependencies</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">All other content distributed as an archive contains a README.TXT with project name, web site, nature, how /where to get help, version, and date.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>All other content distributed as an archive contains a README, in a common plain text markup format, with project name, web site, nature, how /where to get help, version, and date.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">All source and binary distributions contain a README.TXT with project name, web site, how/where to get help, version, date, licence and copyright (or where to find this information), location of entry point into user doc.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>All source and binary distributions contain a README, in a common plain text markup format, with project name, web site, how/where to get help, version, date, licence and copyright (or where to find this information), location of entry point into user doc.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p></p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Binary distributions have instructions for installing the product.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Installation</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Installers allow user to select where to install software.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Installation</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has instructions for installing or accessing the product.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Installation</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">When software is installed, or when a product or service has multiple facets, its contents are organised into sub-directories (e.g. docs for documentation, libs for dependent libraries) or IRL hierarchies (/about, /support, etc.) as appropriate.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Installation</p>
            </div>
        </div>
        <!-- kokkonen -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>When appropriate, installer integrates with external authentication sources (e.g., LDAP)</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Installation</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Installers are available for all relevant platforms (Windows, OSX, Linux, etc.)</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Installation</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Installer sets up necessary environment variables</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Installation</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Tests are provided (or silently performed) to verify the install has succeeded or service/product is fully available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Post-installation</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">When an archive (e.g. TAR.GZ or ZIP) is unpacked, it creates a single directory with the files within. It does not spread its contents all over the current directory.  </p>
            </div>
            <div class="metadata">
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Uninstallers exist, and uninstall every file or warns user of any files that were not removed and where these are.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
    </div> <!-- end Usability:Installabilty-->

    <h3 id="other-security">Security</h3>
    <p>Suggested group ordering: Basic (1), Process (2), Tools (3).</p>
    <div class="criteria">
        <!-- gallagher -->
        <div class="criterion">
            <div class="revisions">
                <p class="original">Software is exposed to a static source code checker (e.g., Coverity)</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Available Tools</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Software authors use PKI (e.g., PGP) to sign releases (source and binary) and make the public key available on their website (and/or public key repos).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Basic</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Authors are aware of and use public secure coding guidlines for their languages/technology. These include specific guidlines published by CERT and OWASP, cover both languages like C/C++, Java, Perl and technologies like Web services adn XSLT.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Process</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Projects have in place (and publicly visable) a security incident response plan.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Process</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Authors perform dynamic testing on their software</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Tools</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Authors work with an external organization that reviews/tests their software.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Process</p>
            </div>
        </div>

        <!-- shepherd -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Sanitizes user input. (eg database apps sanitize for SQL injection, inputs that get displayed as HTML get filtered)</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Web App/API</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Web application defends against Cross-Site Request Forgery (CSRF)</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Web App/API</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Web application defends against Cross-Site Scripting (XSS)</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Web App/API</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>File permissions of web-accessible files (eg User-uploaded files cannot overwrite or delete critical files)</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Web App/API</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>User-uploaded files are not executable, cannot completely fill a disk, </p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Web App/API</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Users cannot view arbitrary files through web app</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Web App/API</p>
            </div>
        </div>
    </div> <!-- end Security -->

    <h3 id="other-performance">Performance</h3>
    <div class="criteria">
        <p>Ed. note: Suggested new category to specifically address performance. Will need something regarding web app/service performance.</p>

        <!-- elliott -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Rough order of time-complexity and memory-complexity are documented.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>It is important to know if the algorithm is efficiently implemented, so the user has an understanding of the scalability and the compute resources required to run the code.</p>
                <h4>Application</h4>
                <p>Library/Module</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Is the algorithm parallelized? Or, does the algorithm scale across multiple CPU cores?</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Knowing if an algorithm is single-threaded or multi-threaded can inform the user as to what compute resources are required, and what the rough performance might be like.  In addition it can allow the user to evaluate it against other comepeting algorithms.</p>
                <h4>Application</h4>
                <p>Library/Module</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Does the algorithm use memory efficiently?</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Does the code require the user to have an enormous amount of system memory, or does it make efficient use of available memory on each compute node?</p>
                <h4>Application</h4>
                <p>Library/Module</p>
            </div>
        </div>

        <!-- shepherd -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Performance requirements are documented. What is the requirement and why (for example, Page X should return in under 3 seconds b/c analytics show our major stakeholders navigate away after waiting for 3 seconds).</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Performance limits are documented. (eg. software performance degrades when trying to analyze anything more than 1 million entities)</p>
            </div>
            <div class="metadata">
            </div>
        </div>
    </div> <!-- end Performance -->
</div> <!-- end guidelines-->





