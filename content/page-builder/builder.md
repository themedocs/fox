---
title: "Builder"
description: "Here’s facts about the Fox builder you should know:"
---

Here’s facts about the Fox builder you should know:

1. The Fox has its own built-in builder. It’s developed for only The Fox theme.
2. The builder means Homepage builder. It’s not a page builder. It’s being used to build homepage only.
3. The builder can be accessed immediately in Customizer > Homepage builder. There’s no further actions needed. You have it immediately after installing the theme. You don’t even need to register license.
4. You can’t create page with The Fox builder. You can’t build category with The Fox builder. Only homepage. We have plans to enforce the builder in the future, but for now, It works for homepage only.
5. You don’t need Elementor or any builder plugins to build Fox’s homepage.
6. You can’t edit Fox’s homepage with Elementor. You can edit it with the built-in builder in Customizer.
7. You can theoretically set an Elementor page as homepage if you don’t want to use Fox’s builder and only want to use Fox’s other features like category, single post.. In that case, there’s no difference between <Elementor + Fox> and <Elementor + a random theme>. There’s no extra functionality of <Elementor + Fox>.

To access homepage builder, please go to **Customizer > Homepage builder**.

![](/fox/assets/builder-1.jpg)

### Some Terminologies

**Section**: Is the highest wrapper. You understand it by common sense, like: section 1, section 2, section Business, section Lifestyle, section Travel.. Your homepage is list of sections. In the picture above, you’ll see 6 sections: Featured posts, Business, Politics, Travel, Main Blog, @Instagram.

![](/fox/assets/terminologies-scaled-1.jpg)

*Click to image to view fullsize.*

**Section name**: Each section has a name to distinguish from each other. In above example, we have names: Featured posts, Business, Politics, Travel, Main Blog, @Instagram. Note that changing the section name doesn’t change its content. This can be a bit confusing. You see a section, say “Business”. But it’s just a conventional name for the section. It doesn’t have to display posts filled under category Business. If you display posts under category Technology, It’s totally fine. It’s confusing when you edit, but It’s technically fine, like you name a dog “Mokey” if you want. Section name is just backend convention. Changing the name won’t change anything in frontend, even the heading.

**Row & column**: If you’re familiar with builder concepts, then row and column are being used for building layout more flexible. Because of the padding convenience, we don’t put columns directly under sections. We put: **Section > Row > Column > Elements**. If your section is one column, you don’t need to complicate it. Just put elements directly under Section like this: **Section > Elements**.

![](/fox/assets/section_structure.jpg)

**Elements/Widgets**: This refers to building elements as you might expect: Post grid, Post list, Post group, Heading, Button.. Don’t get confused with WordPress widgets. When we need to mention WordPress widgets, we’ll always use the term “WordPress widgets” to avoid ambiguity. Sometimes we also call Section, Row, Column as Widget. For instance, we say: “You can drag/drop widgets”, then It means, you can drag/drop sections, columns too besides normal widgets (Post list, post grid, Heading..)

**Heading**: Heading is just a building element, named “Heading”. It’s technically a heading like “Business”, “Technology” but when we say Heading element, we refer to the builder element.

**Builder settings**: You find the builder settings next to the Homepage builder panel.

![](/fox/assets/builder_settings.jpg)

### Actions

#### Add section/widget

To add section, you click “Add section” button.

![](/fox/assets/Screenshot_9.png)

To add a widget, you click “Add widget” button. Note that a widget can only be add directly under a section or a column. That means you have “**Section > Widget**” or “**Section > Row > Column > Widget**“. You never have something like: “Row > Post list” directly.

![](/fox/assets/add_widget.jpg)

#### Expand a section/widget

![](/fox/assets/expand_section.jpg)

#### Reorder widgets

You can use your mouse grab to drag/drop sections/widgets to reorder them.

![](/fox/assets/Screenshot_1-2.png)

#### Delete widget

Note: Delete a widget will delete all sub-widgets inside it.

![](/fox/assets/Screenshot_2-1.png)

#### Duplicate widget

![](/fox/assets/Screenshot_3.png)

#### Edit widget

There are 2 ways you can edit a widget.

1. On the preview screen, when hover elements, you’ll see edit buttons.

![](/fox/assets/edit1-1.jpg)

2. On left panel, when hover element, you also see the edit button.

![](/fox/assets/Screenshot_1-3.png)

After clicking to the “Edit” button, you’ll see a panel like below:

![](/fox/assets/Screenshot_2-2.png)

Options for the element are organized in different tabs. Click to each tab to expand it.

#### Export widget

You can export your widgets to a *json file. This json file can be used:

- as a back up. For instance, you experiment another style, a different setting set but you want to keep a back up so that you can restore it later if you don’t want the new changes.
- to clone a widget. You export it to *json file then import it some where else.
- to reuse in another site/project. For instance, you have 2 different websites using The Fox theme. You want to copy quickly a section from one site into another. You might export it in 1 site, then improt that *json file in another fsite.

You can export a section or a widget. It’ll download a *json file automatically.

![](/fox/assets/Screenshot_3-1.png)

#### Import widget

Import means to import a *json file. You need to have a *json file first. That’s the *json file you have exported before.

**To import a section**: Click “**Section templates**“, then hit “**Import**” button. It’ll ask you to upload *json file. This json file must be exported file of a section. After uploading, a new section will be added.

![](/fox/assets/import_section-1.jpg)

**To import a widget**: Click **Add element > Import**. It’ll ask you to upload *json file. This json file must be exported file of an element. After uploading, a new element will be added.

![](/fox/assets/import_widget.jpg)

#### Insert template

The Fox has some predefined sections/widgets. In fact, each template, aka predefined section/widget, is a *json file that is ready to be imported.

**To insert section template**: Click **Section templates**, It’ll show list of templates to choose from.

![](/fox/assets/section_template.jpg)

After choosing the section template, a new section will be added at the end of builder. You’ll need to drag/drop it to place you want it to be.

![](/fox/assets/newly_added_section.jpg)

**To insert element template**: Click **Add element > Templates**, then choose the template you want to insert.

![](/fox/assets/Screenshot_1-4.png)

### Post Query

This section explains how you can change the way posts being displayed. For now, there are 5 post widgets.

![](/fox/assets/Screenshot_1.jpg)

To edit the post widget, please check the section [Edit widget](/fox/page-builder/builder/#Edit_widget) above. When you edit it, post widget has a “**Query**” tab. Click to “Query” to open it.

![](/fox/assets/Screenshot_2.jpg)

You’ll see lot of settings there.

![](/fox/assets/Screenshot_3.jpg)

You can play around with settings there to change the way posts being displayed, including which category, in which order etc.

![](/fox/assets/Screenshot_4.jpg)
