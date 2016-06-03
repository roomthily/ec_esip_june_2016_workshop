---
layout: guidelines
---

# Draft Software Assessment Guidelines #

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
                    <li><a href="#sustainability-analysability">Analysability</a></li>
                    <li><a href="#sustainability-changeability">Changeability</a></li>
                    <li><a href="#sustainability-community">Community</a></li>
                    <li><a href="#sustainability-evolvability">Evolvability</a></li>
                    <li><a href="#sustainability-governance">Governance</a></li>
                    <li><a href="#sustainability-identity">Identity</a></li>
                    <li><a href="#sustainability-interoperability">Interoperability</a></li>
                    <li><a href="#sustainability-licensing">Licensing</a></li>
                    <li><a href="#sustainability-portability">Portability</a></li>
                    <li><a href="#sustainability-supportability">Supportability</a></li>
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
                    <li><a href="#usability-friendliness">Friendliness</a></li>
                    <li><a href="#usability-installability">Installability</a></li>
                    <li><a href="#usability-learnability">Learnability</a></li>
                    <li><a href="#usability-understandability">Understandability</a></li>
                </ul>
            </li>
            <li><a href="#other">Other</a>
                <ul>
                    <li><a href="#other-security">Security</a></li>
                    <li><a href="#other-preservation">Preservation &amp; Archiving</a></li>
                    <li><a href="#other-credit">Credit</a></li>
                    <li><a href="#other-performance">Performance</a></li>
                    <li><a href="#other-notebooks">Notebooks</a></li>
                </ul>
            </li>
        </ul>
    </div>
</div>

<div class="guidelines">
    <p>We are making a distinction between a project developed within common open source models and a project that is open, meeting EarthCube's requirements, to meet publication, reproducibility and provenance concerns. </p>

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

    <h2 id="sustainability-interoperability">Interoperability</h2>
    <p>Ed. note: criteria needs include project-level criteria (serving data services, consuming data services), validation, cross-project criteria (if any can be identified and evaluated).</p>
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

    <h2 id="sustainability-licensing">Licensing</h2>
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
                <h4>Notes</h4>
                <p>Not always relevant.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site states applicable licences.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Documentation states applicable licences.</p>
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

    <h2 id="sustainability-identity">Identity</h2>
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
                <h4>Notes</h4>
                <p>Conflicts with next criteria.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Project/product/software has a distinct name within its application area. A search by Google on the name plus keywords from the application area throws up the project web site in the first page of matches.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Branding</p>
                <h4>Notes</h4>
                <p>First page results is not controllable by research group - revise statements related to name.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Project/product/software has a logo.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Branding</p>
                <h4>Notes</h4>
                <p>This is difficult to justify for research code.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Project/product/software has its own domain name.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Basic</p>
                <h4>Notes</h4>
                <p>This is difficult to justify for research code and may not be possible due to institutional constraints.</p>
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
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Project/product/software name does not violate an existing trade-mark.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Basic</p>
                <h4>Notes</h4>
                <p>This is difficult to justify for research code.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Project/product/software name is trade-marked.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Advanced</p>
                <h4>Notes</h4>
                <p>This is difficult to justify for research code.</p>
            </div>
        </div>

        <p>form community</p>
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
    </div> <!-- end Sustainability:Identity -->

    <h2 id="usability-documentation">Documentation</h2>
    <div class="criteria">
        <p>[shifted from analysability]</p>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Source code comments are written in an API document generation mark-up language (or language-specific style).</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Documentation identifies the API generation took used.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Documentation describes how to build the documentation.</p>
            </div>
            <div class="metadata">
            </div>
        </div>

        <p>[ordered based on post-it activity]</p>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Code is documented (comment blocks, etc.)</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>API Docs</p>
                <h4>Notes</h4>
                <p>To allow present/future developers to be able to quickly understand and/or modify the software.</p>
                <p>potentially provides an opportunity for misinformation propogation</p>
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
                <p>is this a value judgment</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Does not use terms like “intuitive”, “user friendly”, “easy to use”, “simple” or “obviously”, unless as part of quotes from satisfied users.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Style</p>
                <h4>Notes</h4>
                <p>Request to remove style (writing style) criteria.</p>
                <p>tagged as marketing and not documentation </p>
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
                <p>don't understand this</p>
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
                <p>Request to remove style (writing style) criteria.</p>
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
                <p>usability vs maintenability?</p>
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
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>A link to the documentation is contained in the code. [PID should be used instead of URL]</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Documentation is on the project website or the project website provides a clear link to an externally-hosted documentation web site. [PID over URL]</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Doc Management</p>
                <h4>Notes</h4>
                <p>Code and documentation can be separated.</p>
                <p>Consensus for documentation that is hosted by the project or that is hosted on some third-party site such as Read The Docs but it is not always on the project website.</p>
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
                <p>Request to remove - not relevant in this location.</p>
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
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Documentation is updated to reflect new errors and resolution methods identified. [could be a FAQ - Y or N]</p>
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
                <h4>Notes</h4>
                <p>clarify what QC is</p>
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
                <p>e.g., cook book</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Uses teletype-style fonts for command line inputs and outputs, source code fragments, function names, class names etc.; uses appropriately styled fonts for key information and special terms or links.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Documentation follows commmon styles for displaying code blocks.</p>
                <p class="revision added"><i class="fa fa-pencil fa-fw"></i>Documentation clearly distinguishes between input and output blocks.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>(Style?)</p>
                <h4>Notes</h4>
                <p>If nothing else, code blocks or inline snippets are rendered with monospaced fonts (which is the searchable term in most font browsers).</p>
                <p>Request to remove style (writing style) criteria.</p>
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

    <h2 id="sustainability-testability">Testability</h2>
    <p>Suggested category grouping: project has unit and integration tests (1); tests are run by a continuous integration (CI) system once committed (2). Include coding standards and automated coverage analysis as (3) but less crucial than testing and CI. Reconsider criteria that are commonly provided by a CI system and whether those are suggested criteria on their own merit.</p>
    <p>[add the linting concerns as sub group to testability. &amp; rename testability.]</p>
    <div class="criteria">
        <p>[guidelines for code style testing, replaces analysability]</p>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Code is validated using a linter.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Code adheres to the style guide for the language or to the style guide provided for the project (or project's organization).</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Code validation, related to style, is executed using automated tools (continuous integration tools or Coverity, for example).</p>
            </div>
            <div class="metadata">
            </div>
        </div>

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
    

    <h3 id="sustainability-accessibility">Open Source</h3>
    <p>Ed. note: suggest revisions for three situations - 1) project members are hosting their own repository management system (git, Trac, etc) which does affect public/private access and browsability; 2) project members are using a third party DVCS like GitHub or BitBucket which affects public/private but other aspects are not directly tied to the *project* assessment; c) project members post their software repositories to a domain/research code system which is more related to publication and preservation (but still about whether the code is accessible).</p>
    <p>Merged accessibility &amp; evolvability to capture activities for projects being managed as open source.</p>
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
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Binary distributions are available (whether for free, payment, registration).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Artifacts</p>
                <h4>Notes</h4>
                <p>Not always relevant from an OS release perspective, possibly of value for reproducibility/publication.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Binary distributions are available without the need for any registration or authorisation of access by the project.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Artifacts</p>
                <h4>Notes</h4>
                <p>Not always relevant from an OS release perspective, possibly of value for reproducibility/publication.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Binary distributions are freely available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Artifacts</p>
                <h4>Notes</h4>
                <p>Not always relevant from an OS release perspective, possibly of value for reproducibility/publication.</p>
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
        </div><!-- end Sustainability: Accessibility -->

        <!-- evolvability -->
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

    </div> 

    <p>[Unmodified criteria]</p>
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
                <h4>Notes</h4>
                <p>is this relevant to software? It seems releavnt to data. Not necessarily applicable to all</p>
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
                <h4>Notes</h4>
                <p>where are these? In documentation? SHould this be part of testing?</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">There is a specification of the algorithm against which results can be compared.</p>
            </div>
            <div class="metadata">
                <h4>Application</h4>
                <p>Algorithm | Code</p>
                <h4>Notes</h4>
                <p>is this redundant? Documentation?</p>
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
                <p>Move to Security? Update to better reflect roles, groups, etc, terminology. no password sharing</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Expertise of the originators of the project/product is represented throughout the content as appropriate (e.g., in author pages, references, citations, and about or background pages).</p>
            </div>
            <div class="metadata">
                <h4></h4>
                <p>larger assessment framework but not necessary for software</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Opinions and perspectives are offered only as they relate to the mission of the project, and are clearly identified and put into context.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>larger assessment framework but not necessary for software, would this preclude forum or comments in GitHub issues?</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Presented information and data are consistent throughout the project.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>too subjective, lower priority</p>
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
                <h4>Notes</h4>
                <p>important for end users but difficult to achieve</p>
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
    <p>consider adding to section with licensing (not a high priority for EC)</p>
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
                <h4>Notes</h4>
                <p>Style? Is this common practice or based on language style- or project styleguides?</p>
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
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Documentation states copyright.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site states key roles: who developed/develops the product, funds it, oversees the web site, etc.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Documentation states key roles: who developed/develops the product, funds it, oversees the web site, etc.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Consider shifting to publication/credit.</p>
            </div>
        </div>
    </div> <!-- end Sustainability:Copyright-->


    <h3 id="sustainability-analysability">Analysability</h3>
    <p>[move doc statements to documentation (double-check), check learnability as well]</p>
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
                <h4>Notes</h4>
                <p>wrong category?</p>
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
    <p>[not EC priority]</p>
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
    <p>update for new software publication practices (not paper necessarily) and in a better location (for ESIP)</p>
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
                <p>Flagged for publication/credit binning; also chuck this</p>
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
                <h4>Notes</h4>
                <p>Not always goal of project.</p>
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

    <h3 id="sustainability-governance">Governance</h3>
    <p>[not EC priority]</p>
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
                <h4>Notes</h4>
                <p>Only if relevant (define when for this).</p>
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


    <h3 id="sustainability-portability">Portability</h3>
    <p>Ed. note: this entire section is flagged for review, to be resolved by either condensing the two main concepts (software can be built and run on multiple platforms and web application functions across multiple browsers) into more general criteria or by removing the section altogether and updating related criteria in other sections (such as buildability and documentation criteria related to that).</p>
    <p>[not EC priority]</p>
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
    <p>[not EC priority]</p>
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

    <h2 id="usability">Usability</h2>
    <h3 id="usability-buildability">Buildability</h3>
    <div class="criteria">
        <div class="criterion">
            <div class="revisions">
                <p class="original">All mandatory third-party dependencies or external references are currently available.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Is this evaluatable by an external evaluator (in a timely fashion at least)?</p>
                <p>Not controllable by project</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">All optional third-party dependencies or external references are currently available.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Not controllable by project</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">An automated build (e.g. Make, ANT, custom solution) is used to build any software.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>An automated build (e.g. Make, ANT, Maven, Gradle, or other language-specific build tool) is used to build any software.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Dependency management is used to automatically download dependencies (e.g. ANT, Ivy, Maven or custom solution).</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>This is generally not an option for non-Java compiled code. However, there is a related idea for C and C++...</p>
                <p>Python's pip requirements, ruby has implementations... SO a more general statement is viable.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Source distributions have instructions for building corresponding software.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <!-- gallagher -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Code follows the GNU software guidlines and uses README, NEWS, INSTALL and COPYING files to describe the package (INSTALL includes the build information this case).</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>related to previous statement.</p>
            </div>
        </div>
        <!-- end gallagher -->

        <div class="criterion">
            <div class="revisions">
                <p class="original">Source distributions list all third-party dependencies that are not bundled, along with web addresses, suitable versions, licences and whether these are mandatory or optional.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Not sure this full set of things is common. Version yes, but the rest?</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Tests are provided to verify the build or distribution has succeeded, or service/information is presented as intended.</p>
            </div>
            <div class="metadata">
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has instructions for building the product.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Not always applicable [unknown revision here]</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site lists all third-party dependencies that are not bundled, along with web addresses, suitable versions, licences and whether these are mandatory or optional.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Not sure this full set of things is common. Version yes, but the rest?</p>
            </div>
        </div>

        <!-- gallagher -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Binary and source packages reference third-party code (including the acceptable versions) so that commonly-used tools (e.g., yum, apt-get) will automaticlly fetch those source/binary packages</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>auto updating can break other software. From geoscientist perspective these are valuable but shouldn't be a deal breaker for assessment.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project uses build tools (e.g. automake, etc.) in a way that integrates with linux distro packager's expectations so they can/will build packages for public repos.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>why so specific?</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Project supports common/standard (ad hoc) binary packaing tools (e.g., RPM, python egg). This means that a 'buildable' package provides binaries (or the equivalent) so that it can simply be installed and does not have to be built!</p>
            </div>
            <div class="metadata">
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
                <p><a href="#"></a>https://www.w3.org/standards/webdesign/accessibility, WCAG, Section 508</p>
                <p>specify guideline</p>
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
                <p class="original">Web site lists all third-party dependencies and external references that are not bundled, along with (as appropriate) web addresses, suitable versions, licences and whether these are mandatory or optional. [this material must be contained with the software but not required in web site?]</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Documentation lists all third-party dependencies and external references that are not bundled, along with (as appropriate) web addresses, suitable versions, licences and whether these are mandatory or optional.</p>
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
                <h4>Notes</h4>
                <p>Not controllable.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">All optional third-party dependencies or external references are currently available.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Dependencies</p>
                <h4>Notes</h4>
                <p>Not controllable.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Dependency management is used to automatically download dependencies (e.g. ANT, Ivy, Maven or custom solution).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Dependencies</p>
                <h4>Notes</h4>
                <p>May not apply to all software types - suggest applicable types.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Binary distributions list all third-party dependencies and external references that are not bundled, along with (as appropriate) web addresses, suitable versions, licences and whether these are mandatory or optional.</p>
                <p class="revision"><i class="fa fa-pencil fa-fw"></i>Binary distributions identify all third-party dependencies and external references that are not bundled, along with (as appropriate) web addresses, suitable versions, licences and whether these are mandatory or optional.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Dependencies</p>
                <h4>Notes</h4>
                <p>As applicable</p>
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
                <h4>Notes</h4>
                <p>if needed</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Web site has instructions for installing or accessing the product.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Installation</p>
                <h4>Notes</h4>
                <p>Questioned "web site" as appropriate location for this info - likelier, if project website for example, to get out of date.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">When software is installed, or when a product or service has multiple facets, its contents are organised into sub-directories (e.g. docs for documentation, libs for dependent libraries) or IRL hierarchies (/about, /support, etc.) as appropriate.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Installation</p>
                <h4>Notes</h4>
                <p>Style question. Request to remove.</p>
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
                <h4>Notes</h4>
                <p>too specific</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Installers are available for all relevant platforms (Windows, OSX, Linux, etc.)</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Installation</p>
                <h4>Notes</h4>
                <p>installers provided for target platforms &amp; target platforms are indicated in the documentation.</p>
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
                <h4>Notes</h4>
                <p>Style question. Request to remove.</p>
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="original">Uninstallers exist, and uninstall every file or warns user of any files that were not removed and where these are.</p>
            </div>
            <div class="metadata">
            </div>
        </div>

        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>[Recommended installation is not through curl/wget to an uncontrolled resource.]</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Not uncon=mmon to see this as the installation procedure in GitHub repos so some statement might be appropriate.</p>
            </div>
        </div>
    </div> <!-- end Usability:Installabilty-->

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
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Instructions are provided for many basic use cases.</p>
                <p class="original questioned"><i class="fa fa-warning fa-fw"></i>Instructions are provided supporting all use cases.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>Redundant (relies on some understanding of "basic use case".</p>
                <p>chuck anyway</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="original">Reference guides or contextual specifications (may be simple labels, if clear) are provided for all command line, GUI and configuration options.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>over-documentation</p>
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
                <h4>Notes</h4>
                <p>revise for intended use to make it clearer re: license</p>
            </div>
        </div>
    </div> <!-- end Usability:Understandability -->

    <h2 id="other">Other</h2>

    <h3 id="other-security">Security</h3>
    <p>Suggested group ordering: Basic (1), Process (2), Tools (3).</p>
    <div class="criteria">
        <!-- gallagher -->
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Software is exposed to a static source code checker (e.g., Coverity)</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Available Tools</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Software authors use PKI (e.g., PGP) to sign releases (source and binary) and make the public key available on their website (and/or public key repos).</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Basic</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Authors are aware of and use public secure coding guidlines for their languages/technology. These include specific guidlines published by CERT and OWASP, cover both languages like C/C++, Java, Perl and technologies like Web services adn XSLT.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Process</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Projects have in place (and publicly visable) a security incident response plan.</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Process</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Authors perform dynamic testing on their software</p>
            </div>
            <div class="metadata">
                <h4>Grouping</h4>
                <p>Tools</p>
                <h4>Notes</h4>
                <p>not sure what this means? could add penetration testing.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Authors work with an external organization that reviews/tests their software.</p>
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
                <h4>Notes</h4>
                <p>would like further clarification re: disk filling</p>
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

    <h3 id="other-preservation">Preservation/Archiving</h3>
    <p>Ed. note: review with documentation for duplication - make statement here for documentation archived with code and meets those doc standards.</p>
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
                <h4>Notes</h4>
                <p>specific understanding of software - not applicable broadly.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Review committees consider and recognize software contributions and citations of software.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>not applicable as criteria.</p>
            </div>
        </div>
        <div class="criterion">
            <div class="revisions">
                <p class="revision added"><i class="fa fa-plus-circle fa-fw"></i>Publications about the data cite the software used to create the data.</p>
            </div>
            <div class="metadata">
                <h4>Notes</h4>
                <p>not about software</p>
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
                <p>very system dependent (hpc)</p>
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
                <p>a principle</p>
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
                <p>criteria statement?</p>
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

    <h3 id="other-notebooks">Notebooks</h3>
    <div class="criteria">
        <p>Ed. note: Suggested new category given the popularity of Jupyter/iPython Notebooks (or similar systems) in research settings.</p>
    </div>


</div> <!-- end guidelines-->






