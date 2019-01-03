On {{ page.date_published }}, the SEC published the SEC 13(F) securities list for Q{{ page.quarter }} {{ page.year }}.

The [original PDF](/download/pdfs/{{ page.pdf }}) contains {{ page.c }} entries. {{ page.added }} securities were added and {{ page.deleted }} were marked as deleted. Of the full list, {{ page.duplicates }} were duplicates for a final tally of {{ page.count_deduped }} entries.


{% if page.prev_count %}

Last quarter's 13F – [{{ page.prev_year }}Q{{ page.prev_quarter }}]({{ page.prev_post_filename | relative_url }}) had {{ page.prev_count_deduped }} deduplicated entries, a change of {{ page.prev_count_deduped | minus: page.count_deduped }}. 

{% endif %}


The full list of entries, available for purchase, and you can download a sample below.

**[Download Sample CSV](/download/samples/csv/13flist{{ page.year }}q{{page.quarter}}.csv)**

**[Download Sample Excel](/download/samples/csv/13flist{{ page.year }}q{{page.quarter}}.xlsx)**

{{ sample_table }}