# Bullet FAQ

<img align="right" src="./imgs/logo512.png" width="100px" />

Bullet is a Bullet Journal style diary app.

[TOC]

## Getting started

### Download

Bullet support Android and IOS. You can download from these.

[Android](https://play.google.com/store/apps/details?id=com.mizhichashao.bujo_flutter) [https://play.google.com/store/apps/details?id=com.mizhichashao.bujo_flutter](https://play.google.com/store/apps/details?id=com.mizhichashao.bujo_flutter)

[IOS](https://apps.apple.com/us/app/id1581227244?l=en-us&platform=iphone) [https://apps.apple.com/us/app/id1581227244?l=en-us&platform=iphone](https://apps.apple.com/us/app/id1581227244?l=en-us&platform=iphone)

### About Bullet Journal

<img align="right" src="./imgs/futurelogs.jpg" width="100px" />

#### Index

In Bullet Journal, The first page of your Bullet Journal should be the index. Make a list of the items you’ll be tracking with your bullet journal.

But in **Bullet** there was no index. But you can find a collection from the collection list.

#### Future Log

Important and interesting things in your future can be saved in Future Log.

<img align="right" src="./imgs/monthview.jpg" width="100px" />

There also a Future in **Bullet**, it will display a year's Future Log.

You can add a log and drag to other yeas's logs.

#### Monthly Logs

In Bullet Journal the Monthly Logs can write specific events and get a bird’s eye view of what happened during the month.

But Bullet doesn't has a Monthly Logs. Instead, **Bullet** has a Month View. It will show logs in a monthly view.

<img align="right" src="./imgs/dailylogs.jpg" width="100px" />

#### Daily Logs

The Daily Log is designed for day-to-day use. There is Daily Logs in **Bullet** too.

#### Bullet Journal style symbols

``` - ``` Note

Notes include: facts, ideas, thoughts, and observations. Notes are entries that you want to remember but aren’t immediately or necessarily actionable. This Bullet works well for meeting, lecture, or classroom notes.

``` o ``` Event

Events are date-related entries that can either be scheduled (e.g. “Charlie’s birthday”) or logged after they occur (e.g. “signed the lease”).

``` • ``` Task

Task can be any kind actionable items, it can be change status to Completed, Migrated, Scheduled.

``` x ``` Task Complete

``` > ``` Task Migrated (A task that's been moved forward into the next Monthly Log or a Collection)

``` < ``` Task Scheduled (A task that's been moved backward into the Future Log)

#### Collection

In Bullet Journal, the collection is list for notes and tasks that are related by a common theme or purpose.

In **Bullet**, it also has collections. You can create collections, but you didn't need to add items in collections. What you need is bind collection when you are creating a item and it will auto showed in the Collection Detail Page.

## Basic Tutorial

### Item

#### Create a item

Tap the add btn in Daily Logs page, you can open the add view.

![Item Add View](./imgs/itemaddview.jpg)

Just add the item content and notes (optional) and tap the send btn to save the item!

#### Update item

If you want to edit or del a item, you can drag the item to left in the logs list and you will see two btns: Delete and Edit.

![Item Del or Edit](./imgs/itemdeloredit.jpg)

If you want to change the task status, you can drag the item to right in log list and you will see three task just tap and task status will be changed.

![Update Task Status](./imgs/itemchangetaskstatus.jpg)

### Collection

#### Create a collection

You can tap the add btn in collection list page it will jump to the collection new page.

![Collection Add View](./imgs/collectionadd.jpg)

#### Edit or add sub collection

You can drag the collection to left in collection list page and you will see three btns: Archive, Edit, Add Sub Collection.

![Collection Edit](./imgs/collectionaddsuboredit.jpg)

### Bind items with Collection

If you want to bind item with collection, you should tap the collection btn in edit view and it will show you the bind view. Just select the collection you want to bind and comfirm.

![Item Collection btn](./imgs/itemcollectionbtn.jpg)

![Item Bind Collections](./imgs/itembindcollection.jpg)

You don't need to bind item with the parent collection you just need to bind it to the sub collection. You can see the next image, *Swimming* is the sub collection for *Sport*. When the item only bind with *Swimming*, it will showed in both collection Detail.

![Sub Collection](./imgs/collectionsub.jpg)

![Item bind Result](./imgs/itembindresult.jpg)

![Item bind parent Result](./imgs/itembindparentresult.jpg)

### Mainly Pages Description

You can tap the bottom bar to change the page.

![Bottom Bar](./imgs/bottombar.jpg)

The Btns in bottom bar is: 

**Daily Logs**, the Bullet Journal daily logs page.

**Inbox**, All logs will show in this list and you can also search items here.

**Month View**, the month view is similar with [Monthly Logs](#monthly-logs) .

**Future Logs**, the Bullet Journal future logs page.

**Data Statistics**, your BuJo statistics will be showed here.

**Collection List**, the collection list page.

**Setting**, the setting page.

## Advanced Tutorial

### Collection Setting

#### Collection Type

There are many show types for collection. With different show type, collectoin will showed in a different way.

##### Collection Type - List

With *List* show type, collection detail will show items just line comment item list.

![Collection Detail](./imgs/collectiondetaillist.jpg)

##### Collection Type - Month

With *Month* show type, collection detail will show items in the month view.

![Collection Detail](./imgs/collectiondetailmonth.jpg)

##### Collection Type - Line

With *Month* show type, collection detail will show items in a line chart.

![Collection Detail](./imgs/collectiondetailline.jpg)

##### Collection Type - Bill

With *Month* show type, collection detail will show items just like a bill list.

![Collection Detail](./imgs/collectiondetailbill.jpg)

##### Collection Type - Pie

With *Month* show type, collection detail will show items in a pie chart.

![Collection Detail](./imgs/collectiondetailpie.jpg)

##### Collection Type - Album

With *Month* show type, collection detail will show all image from items just like album.

![Collection Detail](./imgs/collectiondetailalbum.jpg)

##### Collection Type - Address

With *Month* show type, collection detail will show items’s address in a map.

![Collection Detail](./imgs/collectiondetailaddress.jpg)

#### Collection Repetition

How to make a repet task in ***Bullet***, the method is to set a *Repetition* with Collection.

There are four repetition setting: *Daily*, *Weekly*, *Monthly* and *Annually*.

With the repetition setting, a temp task will show in the daily logs. Tap this temp task and it will showed the edit view. You can tap the comfirm btn it will insert a  completed task.

![Collection Detail](./imgs/repettask.jpg)

### Custom UI

#### Change Background Image

You can change background image in *Setting* - *Background Image* or change collection background in collectoin edit page.

![Change Background Image](./imgs/changebg.jpg)

#### Theme Style

There are two theme style for ***Bullet***, *Dart* and *Light*. You can change it in *Setting* - *Theme Style*

![Theme Style](./imgs/themestyle.jpg)

#### Theme Color


There are seven theme color for ***Bullet***. You can change it in *Setting* - *Theme Color*

![Theme Colors](./imgs/themes.jpg)

#### Font Family

You can change custom font family in *Setting* - *Font Family*.

![Font Family](./imgs/fontfamily.jpg)

#### Font Color

There are four tyoe font color: *Font Color*, *Top Font Color*, *Hint Color* and *Bottom Icon Color*.

##### Font Color

Font Color is there base font color.

##### Top Font Color

![Top Font Color](./imgs/fontcolortop.jpg)

##### Hint Color

![Hint Color](./imgs/fontcolorhint.jpg)

##### Bottom Icon Color

![Bottom Icon Color](./imgs/fontcolorbottom.jpg)

### Data Sync

***Bullet*** support WebDav data sync. You can config in *Setting* - *Cloud Sync Settings* with *WebDav Address*, *Username* and *Password*.

### Data Search

You can search in search page or inbox page. Users can not only search for Item content, but also search for information such as Item status and time through some parameters.

```date```, search the specific item data.

```startDate```, search items from this time.

```endDate```, search items to this time.

```bulletType```, search the specific bullet type items. ```1``` - Task, ```2``` - Note, ```3``` - Event.

```taskStatus```, search the specific task status items. ```2``` - Complete, ```-1``` - UnComplete.

You should format the ```data```, ```startDate``` and ```endDate``` with the format ```yyyyMMdd``` like ```20230523```.

Parameter name and Parameter value should joined with a ```:```

You should join parameters with a space.

For Example, find the bulletType is Task, taskStatus is Complete, item date between 20230516 and 20230523 and the item content contain ```test``` string.

```
bulletType:1 taskStatus:2 startDate:20230516 endDate:20230523 test
```