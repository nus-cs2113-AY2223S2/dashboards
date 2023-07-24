<frontmatter>
title: "iP progress dashboard"
</frontmatter>
<p/>

<h1 class="display-4">iP progress dashboard</h1>

<box>

* Details about iP grading are [here]({{ url_module_website }}/admin/ip-grading.html).
* Note that the progress shown here is just a rough guidance as it was generated by an automated script. ==A manual inspection will be done after the final submission== to confirm the script's findings.
* **If an increment you did does not appear as 'done' in the dashboard**, make sure you have pushed the corresponding tag to your fork and the tag matches the increment name exactly. You can even tag past commits if you forgot to tag those commits earlier or the tag you used differs from the expected tag. The increment will be marked as 'done' at the next script run (it runs once a day). Contact the teaching team ==only if the problem is not rectified even after the next update==.
* Meaning of colors/icons:
  * %%{{ icon_info }}%% : you can click on this icon to find more info
  * <span class="badge bg-success">ABC</span> : you have done the corresponding item.
  * <span class="badge bg-info">ABC</span> : you have done the corresponding item which is an optional item (well done!).
  * <span class="badge bg-danger">!~~ABC~~</span> : item overdue, not done yet.
  * <span class="badge bg-dark">!~~ABC~~</span> : item due soon, not done yet.
  * <span class="badge bg-secondary">!~~ABC~~</span> : optional item due soon, not done yet.
* If you have queries about the data shown in this page, please email `{{ module | lower }}@comp.nus.edu.sg`.
* This dashboard is **updated {{ "every 2-3 days" if tic4002 else "daily" }}**.
</box>

<include src="{{ module | lower }}/ip-progress-table-fragment.md" />