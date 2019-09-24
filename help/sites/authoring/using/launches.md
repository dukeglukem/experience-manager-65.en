---
title: Launches
seo-title: Launches
description: Launches enable you to efficiently develop content for a future release. They allow you to make changes ready for future publication, while maintaining your current pages
seo-description: Launches enable you to efficiently develop content for a future release. They allow you to make changes ready for future publication, while maintaining your current pages
uuid: 9bbe1b40-5e4f-4a17-9674-72565ba040b5
contentOwner: Chris Bohnert
products: SG_EXPERIENCEMANAGER/6.5/SITES
content-type: reference
topic-tags: site-features
discoiquuid: f5b85c51-f7f6-44b3-bcfb-151ea2ebdf87
index: y
internal: n
snippet: y
---

# Launches{#launches}

Launches enable you to efficiently develop content for a future release.

A launch is created to allow you to make changes ready for future publication (while maintaining your current pages). After editing and updating your launch pages you promote them back to the source, then activate the source pages (top-level). Promoting duplicates the launch content back to the source pages and can be done either manually or automatically (dependent on fields set when creating and editing the launch).

For example, the seasonal product pages of your online store are updated quarterly so that the featured products align with the current season. To prepare for the next quarterly update, you can create a launch of the appropriate web pages. Throughout the quarter, the following changes are accumulated in the launch copy:

* Changes to the source pages that occur as a result of normal maintenance tasks. These changes are automatically duplicated in the launch pages.
* Edits that are performed directly on the launch pages in preparation for the next quarter.

When the next quarter arrives, you promote the launch pages so that you can publish the source pages (holding the updated content). You can promote either all pages, or only those that you have modified.

Launches can also be:

* Created for multiple root branches. While you could create the launch for the entire site (and do the changes there) this can be impractical as the whole site needs to be copied. When hundreds or even thousands of pages are involved, the system requirements and performance are impacted by both the copy action and later the comparisons required for the promotion tasks.
* Nested (a launch within a launch) to give you the ability to create a launch from an existing launch so that authors can take advantage of changes already made, rather than having to make the same changes multiple times for each launch.

This section descibes how to create, edit and promote (and if necessary [delete](/sites/authoring/using/launches-creating.md#deleting-a-launch)) launch pages from within the Sites console or [the Launches console](#the-launches-console):

* [Creating Launches](/sites/authoring/using/launches-creating.md)
* [Editing Launches](../../../sites/authoring/using/launches-editing.md)
* [Promoting Launches](../../../sites/authoring/using/launches-promoting.md)

### Launches - the Order of Events {#launches-the-order-of-events}

Launches enable you to efficiently develop content for a future release of one or more activated web pages.

Launches allow you to:

* Create a copy of your source pages:

    * The copy is your launch.
    * The top-level source pages are known as **Production**.

        * The source pages can be taken from multiple (separate) branches.

  ![](assets/chlimage_1-111.png)

* Edit the launch configuration:

    * Add or remove pages and/or branches to/from the launch.
    * Edit launch properties; such as **Title**, **Launch Date**, **Production Ready** flag.

* You can promote and publish the content either manually or automatically:

    * Manually:

        * Promote your launch content back to the **Target** (source pages) when it is ready to be published.
        * Publish the content from the source (after promoting back) pages.
        * Promote either all pages, or only modified pages.

    * Automatically - this involves the following:

        * The **Launch**(**Live**) **date** field: this can be set when creating or editing a launch.  
        
        * The **Production Ready** flag: this can only be set when editing a launch.
        * If the **Production Ready** flag is set, the launch will be automatically promoted to the production pages on the specified **Launch**(**Live**) **date**. After the promotion, the production pages are automatically published.  
          If no date has been set, the flag will have no effect.

* Update your source and launch pages in parallel:

    * Changes to the source pages are automatically implemented in the launch copy (if set up as with inheritance; i.e. as a live copy).  
    * Changes to your launch copy can be made without disrupting these automatic updates or the source pages.

  ![](assets/chlimage_1-112.png)

* [Create a nested launch](/sites/authoring/using/launches-creating.md#creating-a-nested-launch) - a launch within a launch:

    * The source is an existing launch.
    * You can [promote a nested launch](../../../sites/authoring/using/launches-promoting.md#promoting-a-nested-launch) to any target; this can be a parent launch or the top-level source pages (Production).

  ![](assets/chlimage_1-113.png)

  >[!CAUTION]
  >
  >Deleting a launch will remove the launch itself and all descendant nested launches.

>[!NOTE]
>
>Creating and editing launches requires access rights to `/content/launches` - as with the default group `content-authors`. 
>
>Please contact your system administrator if you experience any problems.

### The Launches Console {#the-launches-console}

The Launches console provides an overview of your launches and allows you to take actions on those listed. The console can be accessed by:

* The **Tools** Console: **Tools**, **Sites**, **Launches**.

* Or directly with [http://localhost:4502/libs/launches/content/launches.html](http://localhost:4502/libs/launches/content/launches.html)

### Launches in References (Sites Console) {#launches-in-references-sites-console}

1. In the **Sites** console, navigate to the source of the launch(es).
1. Open the **References** rail and select the source page.
1. Select **Launches**, the existing launch(es) will be listed:

   ![](assets/screen-shot_2019-03-05at121901-1.png)

1. Tap/click on the appropriate launch, the list of possible actions will be displayed:

   ![](assets/screen-shot_2019-03-05at121952-1.png)
