# Azure-Portal-Dashboards

**What is dashboard?**

A dashboard is a customizable collection of UI tiles displayed in the Azure portal. You can add, remove, and position tiles to create the exact view you want, then save that view as a dashboard. You can configure multiple dashboards, and you can switch among them as needed. You can even share your dashboards with other team members.

Dashboards give you flexibility in what information to display. For example, you can create dashboards for specific roles within the organization, then use role-based access control (RBAC) to control who can access each dashboard.

Dashboards are stored as JavaScript Object Notation (JSON) files. This format means you can download a dashboard and edit the file directly, then upload it again to Azure or share it with other users. Azure stores dashboards within resource groups, just like any other resource that you can manage within the portal.


**How to create dashboard**

1. In the Azure portal, from the top left-hand side, select **Show portal menu > Dashboard**.

2. Select the Create button, then select **Custom**.

3. At the top left, change **My Dashboard** to **Customer Dashboard**.
   

**How to Add and configure the Clock tile**

1. In the Tile Gallery, find the **Clock** tile and drag it onto the workspace. Place it on the top along the right side of the available space.

2. Select the **Preview** button at the top of the screen, then right-click the **Clock** tile and select **Edit**.

3. On the **Edit clock** pane, change the **Location** to **(UTC-08:00) Pacific Time (US & Canada)**.

4. Under **Time format**, select **24 hour**.

5. Select **Done**, then select **Save** at the top of the screen.

6. Select the **Edit** button at the top of the screen to return to edit mode, then repeat the previous five steps to place a new clock right below the first one. This time, select **(UTC-05:00) Eastern Time (US & Canada)** for the **Location**.

You should now have two clocks on your dashboard, each displaying a different time zone.


**How to Add and Resize tiles**

1. Select the **Edit** button to return to edit mode, then find the **All resources** tile in the Tile Gallery. Drag and drop it in the top left-hand corner of the dashboard workspace.

2. Hover over the new **All resources** tile and select the **Context menu** icon (...), then select the **6 x 6** size.

3. Select the gray corner on the bottom right-hand side of the tile, and drag it up to resize the tile to about 3.5 squares vertically, keeping the horizontal size the same. When you finish resizing, the tile adjusts to the closest available size, **6 x 4**.

4. From the Tile Gallery, drag the **Resource groups** tile onto the workspace. Place it underneath the **All resources** tile.

5. From the Tile Gallery, select the **Metrics chart** tile, and drag it onto the workspace. Place it to the right of the **All resources** tile.

6. Continue to add the following tiles, rearranging them to fit as needed:
   * Help + support
   * Microsoft Entra quick tasks
   * Marketplace

7. After you've added these tiles, select **Save**. The **Customer Dashboard** dashboard that you created appears as your current dashboard.
   

**How to Clone a dashboard***

You now want to create a similar dashboard for some other customers, but with a few changes.

1. Select the **Clone** button.

2. Rename the dashboard from **Clone of Customer Dashboard** to **Microsoft Entra Admin Dashboard**.

3. On the **Resource Groups** tile, select the **Context menu** icon (...), then select **Remove from dashboard** to delete this tile. Select **Save**.

4. Select the **Edit** button at the top of the screen.

5. From the Tile Gallery, locate and add the following tiles:
   * Users and groups
   * User sign-in summary

6. Reposition the tiles as necessary, then select **Save**. The **Microsoft Entra Admin Dashboard** dashboard that you created appears as your current dashboard.
   

**How to Share a dashboard**

You now want to make this dashboard available to other users. In the sandbox environment, you can't share a dashboard with other users. But you can see how you'd publish a shared dashboard by completing the following steps

1. From the Microsoft Entra Admin dashboard, select the **Share** button at the top. The **Sharing + access control** appears.
2. If the **Publish to the 'dashboards' resource group** checkbox is selected, uncheck the box.
3. Select the resource group <your own resource group name> from the **Resource group** dropdown.
4. Select **Publish**.
5. Close the **Sharing + access control** pane.
   

**How to Delete a dashboard**

1. From the dashboard selection drop-down control, ensure that **Microsoft Entra Admin Dashboard** is selected.

2. Select the **Delete** button.

3. In the **Confirmation** message box, check the box to confirm that you want to delete the dashboard, then select **OK**.
   

**How to Reset a dashboard**

1. Ensure that **Customer Dashboard** is selected.

2. Select **Edit**.

3. Right-click on the workspace, and select **Reset to default state**.

4. In the **Reset dashboard to default state** message box, select **Yes**.

You see the Customer Dashboard with the default tiles instead of the edits you made.

5. Select **Save**.

6. Select your name at the top right of the portal.

7. Select **Sign out**.

8. Close your browser

You have created and edited dashboards, shared them, deleted them, and finally, reset them to the default state. Now you understand how to use dashboards to create efficient interfaces showing appropriate information for different roles within an organization.
