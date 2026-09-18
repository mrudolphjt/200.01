100.01 eCourt United States Court System HTML Prototypes

Included files

1. 100-01-court-system-explorer.html
   A tabbed and clickable comparison of the federal court hierarchy and a generalized state court model.

2. 100-01-trial-or-appellate.html
   A six-scenario knowledge check with immediate explanatory feedback.

3. 100-01-build-the-hierarchy.html
   An accessible sequencing activity for the federal hierarchy and a typical state hierarchy. Learners select buttons instead of relying on drag and drop.

4. index.html
   A responsive test page that links to all three activities.

Design and accessibility

- Uses the Journal Technologies white template and brand colors:
  #D920A2, #821293, #2B57A8, #168CBF, #20BCC8, and #33CC99.
- Uses only system fonts, inline CSS, and inline JavaScript. No outside libraries or font requests are required.
- Supports keyboard navigation, visible focus, responsive layouts, reduced motion preferences, and live feedback announcements.
- At standard desktop embed sizes, each activity uses the iframe viewport height so the outer page does not create a scrollbar.
- At narrow widths, high browser zoom, or unusually short embed heights, normal scrolling remains available so content is not clipped.

Publishing and Rippling

1. Upload each HTML file to the approved web host, such as the existing GitHub Pages site.
2. Open the hosted URL directly and test the activity with a keyboard and at narrow browser widths.
3. Add the hosted URL to Rippling. If Rippling retains only the iframe source, use the simplest supported embed:

   <iframe src="FULL_HOSTED_URL"></iframe>

4. Confirm the visible iframe height in Rippling. A responsive page can adjust to the iframe width, but it cannot enlarge a cross-origin iframe controlled by the LMS.
5. Keep a direct link below the embed if Rippling provides a small fixed iframe or if a learner needs to open the activity in a new window.

Content governance

The activities provide a general educational overview. State and local court names, jurisdiction, and appeal paths vary. Complete legal or subject matter expert review before publishing.
