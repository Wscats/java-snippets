# Java Snippets

Detailed Snippets Reference: [英文](https://wscats.github.io/java-snippets/java.html) / [中文](https://wscats.gitee.io/java-snippets/java.html)

|API|Prefix|Description|
|-|-|-|
|`appletResize(${1:int}, ${2:int})`|appletResize|Takes 2 args. Method in interface java.applet.AppletStub  Called when the applet wants to be resized. |
|`ACTION_EVENT_MASK`|ACTION_EVENT_MASK|Takes 0 args. Static variable in class java.awt.AWTEvent  The event mask for selecting action events. |
|`ADJUSTMENT_EVENT_MASK`|ADJUSTMENT_EVENT_MASK|Takes 0 args. Static variable in class java.awt.AWTEvent  The event mask for selecting adjustment events. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class java.awt.AWTEventMulticaster  Handles the actionPerformed event by invoking the  actionPerformed methods on listener-a and listener-b. |
|`add(${1:Listener}, ${2:Listener})`|add|Takes 2 args. Static method in class java.awt.AWTEventMulticaster  Adds action-listener-a with action-listener-b and  returns the resulting multicast listener. |
|`addInternal(${1:EventListener}, ${2:EventListener})`|addInternal|Takes 2 args. Static method in class java.awt.AWTEventMulticaster  Returns the resulting multicast listener from adding listener-a  and listener-b together. |
|`adjustmentValueChanged()`|adjustmentValueChanged|Takes 0 args. Method in class java.awt.AWTEventMulticaster  Handles the adjustmentValueChanged event by invoking the  adjustmentValueChanged methods on listener-a and listener-b. |
|`ancestorMoved()`|ancestorMoved|Takes 0 args. Method in class java.awt.AWTEventMulticaster  Handles the ancestorMoved event by invoking the  ancestorMoved methods on listener-a and listener-b. |
|`ancestorResized()`|ancestorResized|Takes 0 args. Method in class java.awt.AWTEventMulticaster  Handles the ancestorResized event by invoking the  ancestorResized methods on listener-a and listener-b. |
|`addAdjustmentListener()`|addAdjustmentListener|Takes 0 args. Method in interface java.awt.Adjustable  Adds a listener to receive adjustment events when the value of  the adjustable object changes. |
|`AFTER_LAST_LINE`|AFTER_LAST_LINE|Takes 0 args. Static variable in class java.awt.BorderLayout  Synonym for PAGE_END. |
|`AFTER_LINE_ENDS`|AFTER_LINE_ENDS|Takes 0 args. Static variable in class java.awt.BorderLayout  Synonym for LINE_END. |
|`addLayoutComponent(${1:Component}, ${2:Object})`|addLayoutComponent|Takes 2 args. Method in class java.awt.BorderLayout  Adds the specified component to the layout, using the specified  constraint object. |
|`addActionListener()`|addActionListener|Takes 0 args. Method in class java.awt.Button  Adds the specified action listener to receive action events from  this button. |
|`addNotify()`|addNotify|Takes 0 args. Method in class java.awt.Button  Creates the peer of the button. |
|`addNotify()`|addNotify|Takes 0 args. Method in class java.awt.Canvas  Creates the peer of the canvas. |
|`addLayoutComponent(${1:Component}, ${2:Object})`|addLayoutComponent|Takes 2 args. Method in class java.awt.CardLayout  Adds the specified component to this card layout's internal  table of names. |
|`addItemListener()`|addItemListener|Takes 0 args. Method in class java.awt.Checkbox  Adds the specified item listener to receive item events from  this check box. |
|`addNotify()`|addNotify|Takes 0 args. Method in class java.awt.Checkbox  Creates the peer of the Checkbox. |
|`addItemListener()`|addItemListener|Takes 0 args. Method in class java.awt.CheckboxMenuItem  Adds the specified item listener to receive item events from  this check box menu item. |
|`addNotify()`|addNotify|Takes 0 args. Method in class java.awt.CheckboxMenuItem  Creates the peer of the checkbox item. |
|`add()`|add|Takes 0 args. Method in class java.awt.Choice  Adds an item to this Choice menu. |
|`addItem()`|addItem|Takes 0 args. Method in class java.awt.Choice  Obsolete as of Java 2 platform v1.1. |
|`addItemListener()`|addItemListener|Takes 0 args. Method in class java.awt.Choice  Adds the specified item listener to receive item events from  this Choice menu. |
|`addNotify()`|addNotify|Takes 0 args. Method in class java.awt.Choice  Creates the Choice's peer. |
|`accessibleAWTComponentHandler`|accessibleAWTComponentHandler|Takes 0 args. Variable in class java.awt.Component.AccessibleAWTComponent  |
|`accessibleAWTFocusHandler`|accessibleAWTFocusHandler|Takes 0 args. Variable in class java.awt.Component.AccessibleAWTComponent  |
|`addFocusListener()`|addFocusListener|Takes 0 args. Method in class java.awt.Component.AccessibleAWTComponent  Adds the specified focus listener to receive focus events from this  component. |
|`addPropertyChangeListener()`|addPropertyChangeListener|Takes 0 args. Method in class java.awt.Component.AccessibleAWTComponent  Adds a PropertyChangeListener to the listener list. |
|`add()`|add|Takes 0 args. Method in class java.awt.Component  Adds the specified popup menu to the component. |
|`addComponentListener()`|addComponentListener|Takes 0 args. Method in class java.awt.Component  Adds the specified component listener to receive component events from  this component. |
|`addFocusListener()`|addFocusListener|Takes 0 args. Method in class java.awt.Component  Adds the specified focus listener to receive focus events from  this component when this component gains input focus. |
|`addHierarchyBoundsListener()`|addHierarchyBoundsListener|Takes 0 args. Method in class java.awt.Component  Adds the specified hierarchy bounds listener to receive hierarchy  bounds events from this component when the hierarchy to which this  container belongs changes. |
|`addHierarchyListener()`|addHierarchyListener|Takes 0 args. Method in class java.awt.Component  Adds the specified hierarchy listener to receive hierarchy changed  events from this component when the hierarchy to which this container  belongs changes. |
|`addInputMethodListener()`|addInputMethodListener|Takes 0 args. Method in class java.awt.Component  Adds the specified input method listener to receive  input method events from this component. |
|`addKeyListener()`|addKeyListener|Takes 0 args. Method in class java.awt.Component  Adds the specified key listener to receive key events from  this component. |
|`addMouseListener()`|addMouseListener|Takes 0 args. Method in class java.awt.Component  Adds the specified mouse listener to receive mouse events from  this component. |
|`addMouseMotionListener()`|addMouseMotionListener|Takes 0 args. Method in class java.awt.Component  Adds the specified mouse motion listener to receive mouse motion  events from this component. |
|`addMouseWheelListener()`|addMouseWheelListener|Takes 0 args. Method in class java.awt.Component  Adds the specified mouse wheel listener to receive mouse wheel events  from this component. |
|`addNotify()`|addNotify|Takes 0 args. Method in class java.awt.Component  Makes this Component displayable by connecting it to a  native screen resource. |
|`addPropertyChangeListener(${1:String}, ${2:PropertyChangeListener})`|addPropertyChangeListener|Takes 2 args. Method in class java.awt.Component  Adds a PropertyChangeListener to the listener list for a specific  property. |
|`applyComponentOrientation()`|applyComponentOrientation|Takes 0 args. Method in class java.awt.Component  Sets the ComponentOrientation property of this component  and all components contained within it. |
|`areFocusTraversalKeysSet()`|areFocusTraversalKeysSet|Takes 0 args. Method in class java.awt.Component  Returns whether the Set of focus traversal keys for the given focus  traversal operation has been explicitly defined for this Component. |
|`accessibleContainerHandler`|accessibleContainerHandler|Takes 0 args. Variable in class java.awt.Container.AccessibleAWTContainer  |
|`addPropertyChangeListener()`|addPropertyChangeListener|Takes 0 args. Method in class java.awt.Container.AccessibleAWTContainer  Adds a PropertyChangeListener to the listener list. |
|`add(${1:Component}, ${2:Object}, ${3:int})`|add|Takes 3 args. Method in class java.awt.Container  Adds the specified component to this container with the specified  constraints at the specified index. |
|`addContainerListener()`|addContainerListener|Takes 0 args. Method in class java.awt.Container  Adds the specified container listener to receive container events  from this container. |
|`addImpl(${1:Component}, ${2:Object}, ${3:int})`|addImpl|Takes 3 args. Method in class java.awt.Container  Adds the specified component to this container at the specified  index. |
|`addNotify()`|addNotify|Takes 0 args. Method in class java.awt.Container  Makes this Container displayable by connecting it to  a native screen resource. |
|`addPropertyChangeListener(${1:String}, ${2:PropertyChangeListener})`|addPropertyChangeListener|Takes 2 args. Method in class java.awt.Container  Adds a PropertyChangeListener to the listener list for a specific  property. |
|`applyComponentOrientation()`|applyComponentOrientation|Takes 0 args. Method in class java.awt.Container  Sets the ComponentOrientation property of this container  and all components contained within it. |
|`areFocusTraversalKeysSet()`|areFocusTraversalKeysSet|Takes 0 args. Method in class java.awt.Container  Returns whether the Set of focus traversal keys for the given focus  traversal operation has been explicitly defined for this Container. |
|`accept()`|accept|Takes 0 args. Method in class java.awt.ContainerOrderFocusTraversalPolicy  Determines whether a Component is an acceptable choice as the new  focus owner. |
|`accept()`|accept|Takes 0 args. Method in class java.awt.DefaultFocusTraversalPolicy  Determines whether a Component is an acceptable choice as the new  focus owner. |
|`addNotify()`|addNotify|Takes 0 args. Method in class java.awt.Dialog  Makes this Dialog displayable by connecting it to  a native screen resource. |
|`ACTION_EVENT`|ACTION_EVENT|Takes 0 args. Static variable in class java.awt.Event  This event indicates that the user wants some action to occur. |
|`ALT_MASK`|ALT_MASK|Takes 0 args. Static variable in class java.awt.Event  This flag indicates that the Alt key was down when  the event occurred. |
|`arg`|arg|Takes 0 args. Variable in class java.awt.Event  An arbitrary argument of the event. |
|`addNotify()`|addNotify|Takes 0 args. Method in class java.awt.FileDialog  Creates the file dialog's peer. |
|`addLayoutComponent(${1:String}, ${2:Component})`|addLayoutComponent|Takes 2 args. Method in class java.awt.FlowLayout  Adds the specified component to the layout. |
|`addNotify()`|addNotify|Takes 0 args. Method in class java.awt.Frame  Makes this Frame displayable by connecting it to  a native screen resource. |
|`addRenderingHints()`|addRenderingHints|Takes 0 args. Method in class java.awt.Graphics2D  Sets the values of an arbitrary number of preferences for the  rendering algorithms. |
|`ABOVE_BASELINE`|ABOVE_BASELINE|Takes 0 args. Static variable in class java.awt.GridBagConstraints  Possible value for the anchor field. |
|`ABOVE_BASELINE_LEADING`|ABOVE_BASELINE_LEADING|Takes 0 args. Static variable in class java.awt.GridBagConstraints  Possible value for the anchor field. |
|`ABOVE_BASELINE_TRAILING`|ABOVE_BASELINE_TRAILING|Takes 0 args. Static variable in class java.awt.GridBagConstraints  Possible value for the anchor field. |
|`anchor`|anchor|Takes 0 args. Variable in class java.awt.GridBagConstraints  This field is used when the component is smaller than its  display area. |
|`AdjustForGravity(${1:GridBagConstraints}, ${2:Rectangle})`|AdjustForGravity|Takes 2 args. Method in class java.awt.GridBagLayout  This method is obsolete and supplied for backwards  compatability only; new code should call adjustForGravity instead. |
|`ArrangeGrid()`|ArrangeGrid|Takes 0 args. Method in class java.awt.GridBagLayout  This method is obsolete and supplied for backwards  compatability only; new code should call arrangeGrid instead. |
|`addLayoutComponent(${1:String}, ${2:Component})`|addLayoutComponent|Takes 2 args. Method in class java.awt.GridBagLayout  Has no effect, since this layout manager does not use a per-component string. |
|`adjustForGravity(${1:GridBagConstraints}, ${2:Rectangle})`|adjustForGravity|Takes 2 args. Method in class java.awt.GridBagLayout  Adjusts the x, y, width, and height fields to the correct  values depending on the constraint geometry and pads. |
|`arrangeGrid()`|arrangeGrid|Takes 0 args. Method in class java.awt.GridBagLayout  Lays out the grid. |
|`addLayoutComponent(${1:String}, ${2:Component})`|addLayoutComponent|Takes 2 args. Method in class java.awt.GridLayout  Adds the specified component with the specified name to the layout. |
|`accelerationPriority`|accelerationPriority|Takes 0 args. Variable in class java.awt.Image  Priority for accelerating this image. |
|`addItemListener()`|addItemListener|Takes 0 args. Method in interface java.awt.ItemSelectable  Adds a listener to receive item events when the state of an item is  changed by the user. |
|`ALL`|ALL|Takes 0 args. Static variable in class java.awt.JobAttributes.DefaultSelectionType  The DefaultSelectionType instance to use for  specifying that all pages of the job should be printed. |
|`addKeyEventDispatcher()`|addKeyEventDispatcher|Takes 0 args. Method in class java.awt.KeyboardFocusManager  Adds a KeyEventDispatcher to this KeyboardFocusManager's dispatcher  chain. |
|`addKeyEventPostProcessor()`|addKeyEventPostProcessor|Takes 0 args. Method in class java.awt.KeyboardFocusManager  Adds a KeyEventPostProcessor to this KeyboardFocusManager's post-  processor chain. |
|`addPropertyChangeListener(${1:String}, ${2:PropertyChangeListener})`|addPropertyChangeListener|Takes 2 args. Method in class java.awt.KeyboardFocusManager  Adds a PropertyChangeListener to the listener list for a specific  property. |
|`addVetoableChangeListener(${1:String}, ${2:VetoableChangeListener})`|addVetoableChangeListener|Takes 2 args. Method in class java.awt.KeyboardFocusManager  Adds a VetoableChangeListener to the listener list for a specific  property. |
|`addNotify()`|addNotify|Takes 0 args. Method in class java.awt.Label  Creates the peer for this label. |
|`addLayoutComponent(${1:String}, ${2:Component})`|addLayoutComponent|Takes 2 args. Method in interface java.awt.LayoutManager  If the layout manager uses a per-component string,  adds the component comp to the layout,  associating it  with the string specified by name. |
|`addLayoutComponent(${1:Component}, ${2:Object})`|addLayoutComponent|Takes 2 args. Method in interface java.awt.LayoutManager2  Adds the specified component to the layout, using the specified  constraint object. |
|`addFocusListener()`|addFocusListener|Takes 0 args. Method in class java.awt.List.AccessibleAWTList.AccessibleAWTListChild  Adds the specified focus listener to receive focus events from  this component. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class java.awt.List.AccessibleAWTList  |
|`addAccessibleSelection()`|addAccessibleSelection|Takes 0 args. Method in class java.awt.List.AccessibleAWTList  Adds the specified selected item in the object to the object's  selection. |
|`add(${1:String}, ${2:int})`|add|Takes 2 args. Method in class java.awt.List  Adds the specified item to the the scrolling list  at the position indicated by the index. |
|`addActionListener()`|addActionListener|Takes 0 args. Method in class java.awt.List  Adds the specified action listener to receive action events from  this list. |
|`addItemListener()`|addItemListener|Takes 0 args. Method in class java.awt.List  Adds the specified item listener to receive item events from  this list. |
|`addNotify()`|addNotify|Takes 0 args. Method in class java.awt.List  Creates the peer for the list. |
|`ABORTED`|ABORTED|Takes 0 args. Static variable in class java.awt.MediaTracker  Flag indicating that the downloading of media was aborted. |
|`addImage(${1:Image}, ${2:int}, ${3:int}, ${4:int})`|addImage|Takes 4 args. Method in class java.awt.MediaTracker  Adds a scaled image to the list of images being tracked  by this media tracker. |
|`add()`|add|Takes 0 args. Method in class java.awt.Menu  Adds an item with the specified label to this menu. |
|`addNotify()`|addNotify|Takes 0 args. Method in class java.awt.Menu  Creates the menu's peer. |
|`addSeparator()`|addSeparator|Takes 0 args. Method in class java.awt.Menu  Adds a separator line, or a hypen, to the menu at the current position. |
|`add()`|add|Takes 0 args. Method in class java.awt.MenuBar  Adds the specified menu to the menu bar. |
|`addNotify()`|addNotify|Takes 0 args. Method in class java.awt.MenuBar  Creates the menu bar's peer. |
|`addAccessibleSelection()`|addAccessibleSelection|Takes 0 args. Method in class java.awt.MenuComponent.AccessibleAWTMenuComponent  Adds the specified Accessible child of the object  to the object's selection. |
|`addFocusListener()`|addFocusListener|Takes 0 args. Method in class java.awt.MenuComponent.AccessibleAWTMenuComponent  Adds the specified focus listener to receive focus events from this  component. |
|`addActionListener()`|addActionListener|Takes 0 args. Method in class java.awt.MenuItem  Adds the specified action listener to receive action events  from this menu item. |
|`addNotify()`|addNotify|Takes 0 args. Method in class java.awt.MenuItem  Creates the menu item's peer. |
|`A0`|A0|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_A0. |
|`A1`|A1|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_A1. |
|`A10`|A10|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_A10. |
|`A2`|A2|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_A2. |
|`A3`|A3|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_A3. |
|`A4`|A4|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_A4. |
|`A5`|A5|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_A5. |
|`A6`|A6|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_A6. |
|`A7`|A7|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_A7. |
|`A8`|A8|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_A8. |
|`A9`|A9|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_A9. |
|`addNotify()`|addNotify|Takes 0 args. Method in class java.awt.Panel  Creates the Panel's peer. |
|`addPoint(${1:int}, ${2:int})`|addPoint|Takes 2 args. Method in class java.awt.Polygon  Appends the specified coordinates to this Polygon. |
|`addNotify()`|addNotify|Takes 0 args. Method in class java.awt.PopupMenu  Creates the popup menu's peer. |
|`add()`|add|Takes 0 args. Method in class java.awt.Rectangle  Adds a Rectangle to this Rectangle. |
|`add()`|add|Takes 0 args. Method in class java.awt.RenderingHints  Adds all of the keys and corresponding values from the specified  RenderingHints object to this  RenderingHints object. |
|`addImpl(${1:Component}, ${2:Object}, ${3:int})`|addImpl|Takes 3 args. Method in class java.awt.ScrollPane  Adds the specified component to this scroll pane container. |
|`addNotify()`|addNotify|Takes 0 args. Method in class java.awt.ScrollPane  Creates the scroll pane's peer. |
|`addAdjustmentListener()`|addAdjustmentListener|Takes 0 args. Method in class java.awt.ScrollPaneAdjustable  Adds the specified adjustment listener to receive adjustment  events from this ScrollPaneAdjustable. |
|`addAdjustmentListener()`|addAdjustmentListener|Takes 0 args. Method in class java.awt.Scrollbar  Adds the specified adjustment listener to receive instances of  AdjustmentEvent from this scroll bar. |
|`addNotify()`|addNotify|Takes 0 args. Method in class java.awt.Scrollbar  Creates the Scrollbar's peer. |
|`ACTIVE_CAPTION`|ACTIVE_CAPTION|Takes 0 args. Static variable in class java.awt.SystemColor  The array index for the  SystemColor.activeCaption system color. |
|`ACTIVE_CAPTION_BORDER`|ACTIVE_CAPTION_BORDER|Takes 0 args. Static variable in class java.awt.SystemColor  The array index for the  SystemColor.activeCaptionBorder system color. |
|`ACTIVE_CAPTION_TEXT`|ACTIVE_CAPTION_TEXT|Takes 0 args. Static variable in class java.awt.SystemColor  The array index for the  SystemColor.activeCaptionText system color. |
|`activeCaption`|activeCaption|Takes 0 args. Static variable in class java.awt.SystemColor  The color rendered for the window-title background of the currently active window. |
|`activeCaptionBorder`|activeCaptionBorder|Takes 0 args. Static variable in class java.awt.SystemColor  The color rendered for the border around the currently active window. |
|`activeCaptionText`|activeCaptionText|Takes 0 args. Static variable in class java.awt.SystemColor  The color rendered for the window-title text of the currently active window. |
|`add()`|add|Takes 0 args. Method in class java.awt.SystemTray  Adds a TrayIcon to the SystemTray. |
|`addPropertyChangeListener(${1:String}, ${2:PropertyChangeListener})`|addPropertyChangeListener|Takes 2 args. Method in class java.awt.SystemTray  Adds a PropertyChangeListener to the list of listeners for the  specific property. |
|`addNotify()`|addNotify|Takes 0 args. Method in class java.awt.TextArea  Creates the TextArea's peer. |
|`append()`|append|Takes 0 args. Method in class java.awt.TextArea  Appends the given text to the text area's current text. |
|`addNotify()`|addNotify|Takes 0 args. Method in class java.awt.TextComponent  Makes this Component displayable by connecting it to a  native screen resource. |
|`addTextListener()`|addTextListener|Takes 0 args. Method in class java.awt.TextComponent  Adds the specified text event listener to receive text events  from this text component. |
|`addActionListener()`|addActionListener|Takes 0 args. Method in class java.awt.TextField  Adds the specified action listener to receive  action events from this text field. |
|`addNotify()`|addNotify|Takes 0 args. Method in class java.awt.TextField  Creates the TextField's peer. |
|`addAWTEventListener(${1:AWTEventListener}, ${2:long})`|addAWTEventListener|Takes 2 args. Method in class java.awt.Toolkit  Adds an AWTEventListener to receive all AWTEvents dispatched  system-wide that conform to the given eventMask. |
|`addPropertyChangeListener(${1:String}, ${2:PropertyChangeListener})`|addPropertyChangeListener|Takes 2 args. Method in class java.awt.Toolkit  Adds the specified property change listener for the named desktop  property. |
|`areExtraMouseButtonsEnabled()`|areExtraMouseButtonsEnabled|Takes 0 args. Method in class java.awt.Toolkit  Reports whether events from extra mouse buttons are allowed to be processed and posted into  EventQueue. |
|`addActionListener()`|addActionListener|Takes 0 args. Method in class java.awt.TrayIcon  Adds the specified action listener to receive  ActionEvents from this TrayIcon. |
|`addMouseListener()`|addMouseListener|Takes 0 args. Method in class java.awt.TrayIcon  Adds the specified mouse listener to receive mouse events from  this TrayIcon. |
|`addMouseMotionListener()`|addMouseMotionListener|Takes 0 args. Method in class java.awt.TrayIcon  Adds the specified mouse listener to receive mouse-motion  events from this TrayIcon. |
|`addNotify()`|addNotify|Takes 0 args. Method in class java.awt.Window  Makes this Window displayable by creating the connection to its  native screen resource. |
|`addPropertyChangeListener(${1:String}, ${2:PropertyChangeListener})`|addPropertyChangeListener|Takes 2 args. Method in class java.awt.Window  Adds a PropertyChangeListener to the listener list for a specific  property. |
|`addWindowFocusListener()`|addWindowFocusListener|Takes 0 args. Method in class java.awt.Window  Adds the specified window focus listener to receive window events  from this window. |
|`addWindowListener()`|addWindowListener|Takes 0 args. Method in class java.awt.Window  Adds the specified window listener to receive window events from  this window. |
|`addWindowStateListener()`|addWindowStateListener|Takes 0 args. Method in class java.awt.Window  Adds the specified window state listener to receive window  events from this window. |
|`addFlavorListener()`|addFlavorListener|Takes 0 args. Method in class java.awt.datatransfer.Clipboard  Registers the specified FlavorListener to receive  FlavorEvents from this clipboard. |
|`addFlavorForUnencodedNative(${1:String}, ${2:DataFlavor})`|addFlavorForUnencodedNative|Takes 2 args. Method in class java.awt.datatransfer.SystemFlavorMap  Adds a mapping from a single String native to a single  DataFlavor. |
|`addUnencodedNativeForFlavor(${1:DataFlavor}, ${2:String})`|addUnencodedNativeForFlavor|Takes 2 args. Method in class java.awt.datatransfer.SystemFlavorMap  Adds a mapping from the specified DataFlavor (and all  DataFlavors equal to the specified DataFlavor)  to the specified String native. |
|`autoscroll()`|autoscroll|Takes 0 args. Method in interface java.awt.dnd.Autoscroll  notify the Component to autoscroll |
|`ACTION_COPY`|ACTION_COPY|Takes 0 args. Static variable in class java.awt.dnd.DnDConstants  An int representing a "copy" action. |
|`ACTION_COPY_OR_MOVE`|ACTION_COPY_OR_MOVE|Takes 0 args. Static variable in class java.awt.dnd.DnDConstants  An int representing a "copy" or  "move" action. |
|`ACTION_LINK`|ACTION_LINK|Takes 0 args. Static variable in class java.awt.dnd.DnDConstants  An int representing a "link" action. |
|`ACTION_MOVE`|ACTION_MOVE|Takes 0 args. Static variable in class java.awt.dnd.DnDConstants  An int representing a "move" action. |
|`ACTION_NONE`|ACTION_NONE|Takes 0 args. Static variable in class java.awt.dnd.DnDConstants  An int representing no action. |
|`ACTION_REFERENCE`|ACTION_REFERENCE|Takes 0 args. Static variable in class java.awt.dnd.DnDConstants  An int representing a "reference"  action (synonym for ACTION_LINK). |
|`addDragGestureListener()`|addDragGestureListener|Takes 0 args. Method in class java.awt.dnd.DragGestureRecognizer  Register a new DragGestureListener. |
|`appendEvent()`|appendEvent|Takes 0 args. Method in class java.awt.dnd.DragGestureRecognizer  Listeners registered on the Component by this Recognizer shall record  all Events that are recognized as part of the series of Events that go  to comprise a Drag and Drop initiating gesture via this API. |
|`addDragSourceListener()`|addDragSourceListener|Takes 0 args. Method in class java.awt.dnd.DragSource  Adds the specified DragSourceListener to this  DragSource to receive drag source events during drag  operations intiated with this DragSource. |
|`addDragSourceMotionListener()`|addDragSourceMotionListener|Takes 0 args. Method in class java.awt.dnd.DragSource  Adds the specified DragSourceMotionListener to this  DragSource to receive drag motion events during drag  operations intiated with this DragSource. |
|`addDragSourceListener()`|addDragSourceListener|Takes 0 args. Method in class java.awt.dnd.DragSourceContext  Add a DragSourceListener to this  DragSourceContext if one has not already been added. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class java.awt.dnd.DropTarget.DropTargetAutoScroller  cause autoscroll to occur |
|`addDropTargetListener()`|addDropTargetListener|Takes 0 args. Method in class java.awt.dnd.DropTarget  Adds a new DropTargetListener (UNICAST SOURCE). |
|`addNotify()`|addNotify|Takes 0 args. Method in class java.awt.dnd.DropTarget  Notify the DropTarget that it has been associated with a Component    This method is usually called from java.awt.Component.addNotify() of  the Component associated with this DropTarget to notify the DropTarget  that a ComponentPeer has been associated with that Component. |
|`acceptDrag()`|acceptDrag|Takes 0 args. Method in class java.awt.dnd.DropTargetContext  accept the Drag. |
|`acceptDrop()`|acceptDrop|Takes 0 args. Method in class java.awt.dnd.DropTargetContext  called to signal that the drop is acceptable  using the specified operation. |
|`addNotify()`|addNotify|Takes 0 args. Method in class java.awt.dnd.DropTargetContext  Called when associated with the DropTargetContextPeer. |
|`acceptDrag()`|acceptDrag|Takes 0 args. Method in class java.awt.dnd.DropTargetDragEvent  Accepts the drag. |
|`acceptDrop()`|acceptDrop|Takes 0 args. Method in class java.awt.dnd.DropTargetDropEvent  accept the drop, using the specified action. |
|`ACTION_FIRST`|ACTION_FIRST|Takes 0 args. Static variable in class java.awt.event.ActionEvent  The first number in the range of ids used for action events. |
|`ACTION_LAST`|ACTION_LAST|Takes 0 args. Static variable in class java.awt.event.ActionEvent  The last number in the range of ids used for action events. |
|`ACTION_PERFORMED`|ACTION_PERFORMED|Takes 0 args. Static variable in class java.awt.event.ActionEvent  This event id indicates that a meaningful action occured. |
|`ALT_MASK`|ALT_MASK|Takes 0 args. Static variable in class java.awt.event.ActionEvent  The alt modifier. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in interface java.awt.event.ActionListener  Invoked when an action occurs. |
|`ADJUSTMENT_FIRST`|ADJUSTMENT_FIRST|Takes 0 args. Static variable in class java.awt.event.AdjustmentEvent  Marks the first integer id for the range of adjustment event ids. |
|`ADJUSTMENT_LAST`|ADJUSTMENT_LAST|Takes 0 args. Static variable in class java.awt.event.AdjustmentEvent  Marks the last integer id for the range of adjustment event ids. |
|`ADJUSTMENT_VALUE_CHANGED`|ADJUSTMENT_VALUE_CHANGED|Takes 0 args. Static variable in class java.awt.event.AdjustmentEvent  The adjustment value changed event. |
|`adjustmentValueChanged()`|adjustmentValueChanged|Takes 0 args. Method in interface java.awt.event.AdjustmentListener  Invoked when the value of the adjustable has changed. |
|`ancestorMoved()`|ancestorMoved|Takes 0 args. Method in class java.awt.event.HierarchyBoundsAdapter  Called when an ancestor of the source is moved. |
|`ancestorResized()`|ancestorResized|Takes 0 args. Method in class java.awt.event.HierarchyBoundsAdapter  Called when an ancestor of the source is resized. |
|`ancestorMoved()`|ancestorMoved|Takes 0 args. Method in interface java.awt.event.HierarchyBoundsListener  Called when an ancestor of the source is moved. |
|`ancestorResized()`|ancestorResized|Takes 0 args. Method in interface java.awt.event.HierarchyBoundsListener  Called when an ancestor of the source is resized. |
|`ANCESTOR_MOVED`|ANCESTOR_MOVED|Takes 0 args. Static variable in class java.awt.event.HierarchyEvent  The event id indicating an ancestor-Container was moved. |
|`ANCESTOR_RESIZED`|ANCESTOR_RESIZED|Takes 0 args. Static variable in class java.awt.event.HierarchyEvent  The event id indicating an ancestor-Container was resized. |
|`ALT_DOWN_MASK`|ALT_DOWN_MASK|Takes 0 args. Static variable in class java.awt.event.InputEvent  The Alt key extended modifier constant. |
|`ALT_GRAPH_DOWN_MASK`|ALT_GRAPH_DOWN_MASK|Takes 0 args. Static variable in class java.awt.event.InputEvent  The AltGraph key extended modifier constant. |
|`ALT_GRAPH_MASK`|ALT_GRAPH_MASK|Takes 0 args. Static variable in class java.awt.event.InputEvent  The AltGraph key modifier constant. |
|`ALT_MASK`|ALT_MASK|Takes 0 args. Static variable in class java.awt.event.InputEvent  The Alt key modifier constant. |
|`ALL_RANGES`|ALL_RANGES|Takes 0 args. Static variable in class java.awt.font.NumericShaper  Identifies all ranges, for full contextual shaping. |
|`ARABIC`|ARABIC|Takes 0 args. Static variable in class java.awt.font.NumericShaper  Identifies the ARABIC range and decimal base. |
|`afterOffset()`|afterOffset|Takes 0 args. Static method in class java.awt.font.TextHitInfo  Creates a TextHitInfo at the specified offset,  associated with the character after the offset. |
|`add()`|add|Takes 0 args. Method in class java.awt.geom.Area  Adds the shape of the specified Area to the  shape of this Area. |
|`append(${1:PathIterator}, ${2:boolean})`|append|Takes 2 args. Method in class java.awt.geom.Path2D.Double  Appends the geometry of the specified  PathIterator object  to the path, possibly connecting the new geometry to the existing  path segments with a line segment. |
|`append(${1:PathIterator}, ${2:boolean})`|append|Takes 2 args. Method in class java.awt.geom.Path2D.Float  Appends the geometry of the specified  PathIterator object  to the path, possibly connecting the new geometry to the existing  path segments with a line segment. |
|`append(${1:PathIterator}, ${2:boolean})`|append|Takes 2 args. Method in class java.awt.geom.Path2D  Appends the geometry of the specified  PathIterator object  to the path, possibly connecting the new geometry to the existing  path segments with a line segment. |
|`add()`|add|Takes 0 args. Method in class java.awt.geom.Rectangle2D  Adds a Rectangle2D object to this  Rectangle2D. |
|`archeight`|archeight|Takes 0 args. Variable in class java.awt.geom.RoundRectangle2D.Double  The height of the arc that rounds off the corners. |
|`arcwidth`|arcwidth|Takes 0 args. Variable in class java.awt.geom.RoundRectangle2D.Double  The width of the arc that rounds off the corners. |
|`archeight`|archeight|Takes 0 args. Variable in class java.awt.geom.RoundRectangle2D.Float  The height of the arc that rounds off the corners. |
|`arcwidth`|arcwidth|Takes 0 args. Variable in class java.awt.geom.RoundRectangle2D.Float  The width of the arc that rounds off the corners. |
|`activate()`|activate|Takes 0 args. Method in interface java.awt.im.spi.InputMethod  Activates the input method for immediate input processing. |
|`addTileObserver()`|addTileObserver|Takes 0 args. Method in class java.awt.image.BufferedImage  Adds a tile observer. |
|`addConsumer()`|addConsumer|Takes 0 args. Method in class java.awt.image.FilteredImageSource  Adds the specified ImageConsumer  to the list of consumers interested in data for the filtered image. |
|`ABORT`|ABORT|Takes 0 args. Static variable in interface java.awt.image.ImageObserver  This flag in the infoflags argument to imageUpdate indicates that  an image which was being tracked asynchronously was aborted before  production was complete. |
|`ALLBITS`|ALLBITS|Takes 0 args. Static variable in interface java.awt.image.ImageObserver  This flag in the infoflags argument to imageUpdate indicates that  a static image which was previously drawn is now complete and can  be drawn again in its final form. |
|`addConsumer()`|addConsumer|Takes 0 args. Method in interface java.awt.image.ImageProducer  Registers an ImageConsumer with the  ImageProducer for access to the image data  during a later reconstruction of the Image. |
|`addConsumer()`|addConsumer|Takes 0 args. Method in class java.awt.image.MemoryImageSource  Adds an ImageConsumer to the list of consumers interested in  data for this image. |
|`abortGrabbing()`|abortGrabbing|Takes 0 args. Method in class java.awt.image.PixelGrabber  Request the PixelGrabber to abort the image fetch. |
|`addTileObserver()`|addTileObserver|Takes 0 args. Method in interface java.awt.image.WritableRenderedImage  Adds an observer. |
|`add()`|add|Takes 0 args. Method in class java.awt.image.renderable.ParameterBlock  Adds a Short to the list of parameters. |
|`addSource()`|addSource|Takes 0 args. Method in class java.awt.image.renderable.ParameterBlock  Adds an image to end of the list of sources. |
|`addConsumer()`|addConsumer|Takes 0 args. Method in class java.awt.image.renderable.RenderableImageProducer  Adds an ImageConsumer to the list of consumers interested in  data for this image. |
|`append(${1:Printable}, ${2:PageFormat}, ${3:int})`|append|Takes 3 args. Method in class java.awt.print.Book  Appends numPages pages to the end of this  Book. |
|`activate()`|activate|Takes 0 args. Method in interface java.beans.AppletInitializer    Activate, and/or mark Applet active. |
|`addPropertyChangeListener()`|addPropertyChangeListener|Takes 0 args. Method in interface java.beans.Customizer  Register a listener for the PropertyChange event. |
|`attributeNames()`|attributeNames|Takes 0 args. Method in class java.beans.FeatureDescriptor  Gets an enumeration of the locale-independent names of this  feature. |
|`addPropertyChangeListener(${1:String}, ${2:PropertyChangeListener})`|addPropertyChangeListener|Takes 2 args. Method in class java.beans.PropertyChangeSupport  Add a PropertyChangeListener for a specific property. |
|`addPropertyChangeListener()`|addPropertyChangeListener|Takes 0 args. Method in interface java.beans.PropertyEditor  Adds a listener for the value change. |
|`addPropertyChangeListener()`|addPropertyChangeListener|Takes 0 args. Method in class java.beans.PropertyEditorSupport  Adds a listener for the value change. |
|`addVetoableChangeListener(${1:String}, ${2:VetoableChangeListener})`|addVetoableChangeListener|Takes 2 args. Method in class java.beans.VetoableChangeSupport  Add a VetoableChangeListener for a specific property. |
|`avoidingGui()`|avoidingGui|Takes 0 args. Method in interface java.beans.Visibility  Determines whether this bean is avoiding using a GUI. |
|`addBeanContextMembershipListener()`|addBeanContextMembershipListener|Takes 0 args. Method in interface java.beans.beancontext.BeanContext  Adds the specified BeanContextMembershipListener  to receive BeanContextMembershipEvents from  this BeanContext whenever it adds  or removes a child Component(s). |
|`addPropertyChangeListener(${1:String}, ${2:PropertyChangeListener})`|addPropertyChangeListener|Takes 2 args. Method in interface java.beans.beancontext.BeanContextChild  Adds a PropertyChangeListener  to this BeanContextChild  in order to receive a PropertyChangeEvent  whenever the specified property has changed. |
|`addVetoableChangeListener(${1:String}, ${2:VetoableChangeListener})`|addVetoableChangeListener|Takes 2 args. Method in interface java.beans.beancontext.BeanContextChild  Adds a VetoableChangeListener to  this BeanContextChild  to receive events whenever the specified property changes. |
|`addPropertyChangeListener(${1:String}, ${2:PropertyChangeListener})`|addPropertyChangeListener|Takes 2 args. Method in class java.beans.beancontext.BeanContextChildSupport  Add a PropertyChangeListener for a specific property. |
|`addVetoableChangeListener(${1:String}, ${2:VetoableChangeListener})`|addVetoableChangeListener|Takes 2 args. Method in class java.beans.beancontext.BeanContextChildSupport  Add a VetoableChangeListener for a specific property. |
|`addBeanContextServicesListener()`|addBeanContextServicesListener|Takes 0 args. Method in interface java.beans.beancontext.BeanContextServices  Adds a BeanContextServicesListener to this BeanContext |
|`addService(${1:Class}, ${2:BeanContextServiceProvider})`|addService|Takes 2 args. Method in interface java.beans.beancontext.BeanContextServices  Adds a service to this BeanContext. |
|`addBeanContextServicesListener()`|addBeanContextServicesListener|Takes 0 args. Method in class java.beans.beancontext.BeanContextServicesSupport  add a BeanContextServicesListener |
|`addService(${1:Class}, ${2:BeanContextServiceProvider}, ${3:boolean})`|addService|Takes 3 args. Method in class java.beans.beancontext.BeanContextServicesSupport  add a service |
|`add()`|add|Takes 0 args. Method in class java.beans.beancontext.BeanContextSupport  Adds/nests a child within this BeanContext. |
|`addAll()`|addAll|Takes 0 args. Method in class java.beans.beancontext.BeanContextSupport  add Collection to set of Children (Unsupported)  implementations must synchronized on the hierarchy lock and "children" protected field |
|`addBeanContextMembershipListener()`|addBeanContextMembershipListener|Takes 0 args. Method in class java.beans.beancontext.BeanContextSupport  Adds a BeanContextMembershipListener |
|`avoidingGui()`|avoidingGui|Takes 0 args. Method in class java.beans.beancontext.BeanContextSupport  Used to determine if the BeanContext  child is avoiding using its GUI. |
|`available()`|available|Takes 0 args. Method in class java.io.BufferedInputStream  Returns an estimate of the number of bytes that can be read (or  skipped over) from this input stream without blocking by the next  invocation of a method for this input stream. |
|`available()`|available|Takes 0 args. Method in class java.io.ByteArrayInputStream  Returns the number of remaining bytes that can be read (or skipped over)  from this input stream. |
|`append(${1:CharSequence}, ${2:int}, ${3:int})`|append|Takes 3 args. Method in class java.io.CharArrayWriter  Appends a subsequence of the specified character sequence to this writer. |
|`accept()`|accept|Takes 0 args. Method in interface java.io.FileFilter  Tests whether or not the specified abstract pathname should be  included in a pathname list. |
|`available()`|available|Takes 0 args. Method in class java.io.FileInputStream  Returns an estimate of the number of remaining bytes that can be read (or  skipped over) from this input stream without blocking by the next  invocation of a method for this input stream. |
|`accept(${1:File}, ${2:String})`|accept|Takes 2 args. Method in interface java.io.FilenameFilter  Tests if a specified file should be included in a file list. |
|`available()`|available|Takes 0 args. Method in class java.io.FilterInputStream  Returns an estimate of the number of bytes that can be read (or  skipped over) from this input stream without blocking by the next  caller of a method for this input stream. |
|`available()`|available|Takes 0 args. Method in class java.io.InputStream  Returns an estimate of the number of bytes that can be read (or  skipped over) from this input stream without blocking by the next  invocation of a method for this input stream. |
|`available()`|available|Takes 0 args. Method in interface java.io.ObjectInput  Returns the number of bytes that can be read  without blocking. |
|`available()`|available|Takes 0 args. Method in class java.io.ObjectInputStream  Returns the number of bytes that can be read without blocking. |
|`annotateClass()`|annotateClass|Takes 0 args. Method in class java.io.ObjectOutputStream  Subclasses may implement this method to allow class data to be stored in  the stream. |
|`annotateProxyClass()`|annotateProxyClass|Takes 0 args. Method in class java.io.ObjectOutputStream  Subclasses may implement this method to store custom data in the stream  along with descriptors for dynamic proxy classes. |
|`available()`|available|Takes 0 args. Method in class java.io.PipedInputStream  Returns the number of bytes that can be read from this input  stream without blocking. |
|`append(${1:CharSequence}, ${2:int}, ${3:int})`|append|Takes 3 args. Method in class java.io.PrintStream  Appends a subsequence of the specified character sequence to this output  stream. |
|`append(${1:CharSequence}, ${2:int}, ${3:int})`|append|Takes 3 args. Method in class java.io.PrintWriter  Appends a subsequence of the specified character sequence to this writer. |
|`available()`|available|Takes 0 args. Method in class java.io.PushbackInputStream  Returns an estimate of the number of bytes that can be read (or  skipped over) from this input stream without blocking by the next  invocation of a method for this input stream. |
|`available()`|available|Takes 0 args. Method in class java.io.SequenceInputStream  Returns an estimate of the number of bytes that can be read (or  skipped over) from the current underlying input stream without  blocking by the next invocation of a method for the current  underlying input stream. |
|`append(${1:CharSequence}, ${2:int}, ${3:int})`|append|Takes 3 args. Method in class java.io.StringWriter  Appends a subsequence of the specified character sequence to this writer. |
|`append(${1:CharSequence}, ${2:int}, ${3:int})`|append|Takes 3 args. Method in class java.io.Writer  Appends a subsequence of the specified character sequence to this writer. |
|`append(${1:CharSequence}, ${2:int}, ${3:int})`|append|Takes 3 args. Method in interface java.lang.Appendable  Appends a subsequence of the specified character sequence to this  Appendable. |
|`AEGEAN_NUMBERS`|AEGEAN_NUMBERS|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Aegean Numbers" Unicode character block. |
|`ALCHEMICAL_SYMBOLS`|ALCHEMICAL_SYMBOLS|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Alchemical Symbols" Unicode character block. |
|`ALPHABETIC_PRESENTATION_FORMS`|ALPHABETIC_PRESENTATION_FORMS|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Alphabetic Presentation Forms" Unicode character block. |
|`ANCIENT_GREEK_MUSICAL_NOTATION`|ANCIENT_GREEK_MUSICAL_NOTATION|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Ancient Greek Musical Notation" Unicode character  block. |
|`ANCIENT_GREEK_NUMBERS`|ANCIENT_GREEK_NUMBERS|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Ancient Greek Numbers" Unicode character block. |
|`ANCIENT_SYMBOLS`|ANCIENT_SYMBOLS|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Ancient Symbols" Unicode character block. |
|`ARABIC`|ARABIC|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Arabic" Unicode character block. |
|`ARABIC_PRESENTATION_FORMS_A`|ARABIC_PRESENTATION_FORMS_A|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Arabic Presentation Forms-A" Unicode character  block. |
|`ARABIC_PRESENTATION_FORMS_B`|ARABIC_PRESENTATION_FORMS_B|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Arabic Presentation Forms-B" Unicode character block. |
|`ARABIC_SUPPLEMENT`|ARABIC_SUPPLEMENT|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Arabic Supplement" Unicode character block. |
|`ARMENIAN`|ARMENIAN|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Armenian" Unicode character block. |
|`ARROWS`|ARROWS|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Arrows" Unicode character block. |
|`AVESTAN`|AVESTAN|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Avestan" Unicode character block. |
|`asSubclass()`|asSubclass|Takes 0 args. Method in class java.lang.Class  Casts this Class object to represent a subclass of the class  represented by the specified class object. |
|`abs()`|abs|Takes 0 args. Static method in class java.lang.Math  Returns the absolute value of a long value. |
|`acos()`|acos|Takes 0 args. Static method in class java.lang.Math  Returns the arc cosine of a value; the returned angle is in the  range 0.0 through pi. |
|`asin()`|asin|Takes 0 args. Static method in class java.lang.Math  Returns the arc sine of a value; the returned angle is in the  range -pi/2 through pi/2. |
|`atan()`|atan|Takes 0 args. Static method in class java.lang.Math  Returns the arc tangent of a value; the returned angle is in the  range -pi/2 through pi/2. |
|`atan2(${1:double}, ${2:double})`|atan2|Takes 2 args. Static method in class java.lang.Math  Returns the angle theta from the conversion of rectangular  coordinates (x, y) to polar  coordinates (r, theta). |
|`appendTo()`|appendTo|Takes 0 args. Static method in class java.lang.ProcessBuilder.Redirect  Returns a redirect to append to the specified file. |
|`addShutdownHook()`|addShutdownHook|Takes 0 args. Method in class java.lang.Runtime  Registers a new virtual-machine shutdown hook. |
|`availableProcessors()`|availableProcessors|Takes 0 args. Method in class java.lang.Runtime  Returns the number of processors available to the Java virtual machine. |
|`abs()`|abs|Takes 0 args. Static method in class java.lang.StrictMath  Returns the absolute value of a long value. |
|`acos()`|acos|Takes 0 args. Static method in class java.lang.StrictMath  Returns the arc cosine of a value; the returned angle is in the  range 0.0 through pi. |
|`asin()`|asin|Takes 0 args. Static method in class java.lang.StrictMath  Returns the arc sine of a value; the returned angle is in the  range -pi/2 through pi/2. |
|`atan()`|atan|Takes 0 args. Static method in class java.lang.StrictMath  Returns the arc tangent of a value; the returned angle is in the  range -pi/2 through pi/2. |
|`atan2(${1:double}, ${2:double})`|atan2|Takes 2 args. Static method in class java.lang.StrictMath  Returns the angle theta from the conversion of rectangular  coordinates (x, y) to polar  coordinates (r, theta). |
|`append()`|append|Takes 0 args. Method in class java.lang.StringBuffer  |
|`appendCodePoint()`|appendCodePoint|Takes 0 args. Method in class java.lang.StringBuffer  |
|`append()`|append|Takes 0 args. Method in class java.lang.StringBuilder  |
|`appendCodePoint()`|appendCodePoint|Takes 0 args. Method in class java.lang.StringBuilder  |
|`arraycopy(${1:Object}, ${2:int}, ${3:Object}, ${4:int}, ${5:int})`|arraycopy|Takes 5 args. Static method in class java.lang.System  Copies an array from the specified source array, beginning at the  specified position, to the specified position of the destination array. |
|`activeCount()`|activeCount|Takes 0 args. Static method in class java.lang.Thread  Returns an estimate of the number of active threads in the current  thread's thread group and its  subgroups. |
|`activeCount()`|activeCount|Takes 0 args. Method in class java.lang.ThreadGroup  Returns an estimate of the number of active threads in this thread  group and its subgroups. |
|`activeGroupCount()`|activeGroupCount|Takes 0 args. Method in class java.lang.ThreadGroup  Returns an estimate of the number of active groups in this  thread group and its subgroups. |
|`addSuppressed()`|addSuppressed|Takes 0 args. Method in class java.lang.Throwable  Appends the specified exception to the exceptions that were  suppressed in order to deliver this exception. |
|`annotationType()`|annotationType|Takes 0 args. Method in interface java.lang.annotation.Annotation  Returns the annotation type of this annotation. |
|`annotationType()`|annotationType|Takes 0 args. Method in exception java.lang.annotation.IncompleteAnnotationException  Returns the Class object for the annotation type with the  missing element. |
|`addTransformer(${1:ClassFileTransformer}, ${2:boolean})`|addTransformer|Takes 2 args. Method in interface java.lang.instrument.Instrumentation  Registers the supplied transformer. |
|`appendToBootstrapClassLoaderSearch()`|appendToBootstrapClassLoaderSearch|Takes 0 args. Method in interface java.lang.instrument.Instrumentation  Specifies a JAR file with instrumentation classes to be defined by the  bootstrap class loader. |
|`appendToSystemClassLoaderSearch()`|appendToSystemClassLoaderSearch|Takes 0 args. Method in interface java.lang.instrument.Instrumentation  Specifies a JAR file with instrumentation classes to be defined by the  system class loader. |
|`asCollector(${1:Class}, ${2:int})`|asCollector|Takes 2 args. Method in class java.lang.invoke.MethodHandle  Makes an array-collecting method handle, which accepts a given number of trailing  positional arguments and collects them into an array argument. |
|`asFixedArity()`|asFixedArity|Takes 0 args. Method in class java.lang.invoke.MethodHandle  Makes a fixed arity method handle which is otherwise  equivalent to the the current method handle. |
|`asSpreader(${1:Class}, ${2:int})`|asSpreader|Takes 2 args. Method in class java.lang.invoke.MethodHandle  Makes an array-spreading method handle, which accepts a trailing array argument  and spreads its elements as positional arguments. |
|`asType()`|asType|Takes 0 args. Method in class java.lang.invoke.MethodHandle  Produces an adapter method handle which adapts the type of the  current method handle to a new type. |
|`asVarargsCollector()`|asVarargsCollector|Takes 0 args. Method in class java.lang.invoke.MethodHandle  Makes a variable arity adapter which is able to accept  any number of trailing positional arguments and collect them  into an array argument. |
|`asInterfaceInstance(${1:Class}, ${2:MethodHandle})`|asInterfaceInstance|Takes 2 args. Static method in class java.lang.invoke.MethodHandleProxies  Produces an instance of the given single-method interface which redirects  its calls to the given method handle. |
|`arrayElementGetter()`|arrayElementGetter|Takes 0 args. Static method in class java.lang.invoke.MethodHandles  Produces a method handle giving read access to elements of an array. |
|`arrayElementSetter()`|arrayElementSetter|Takes 0 args. Static method in class java.lang.invoke.MethodHandles  Produces a method handle giving write access to elements of an array. |
|`appendParameterTypes()`|appendParameterTypes|Takes 0 args. Method in class java.lang.invoke.MethodType  Finds or creates a method type with additional parameter types. |
|`ABSTRACT`|ABSTRACT|Takes 0 args. Static variable in class java.lang.reflect.Modifier  The int value representing the abstract  modifier. |
|`abs()`|abs|Takes 0 args. Method in class java.math.BigDecimal  Returns a BigDecimal whose value is the absolute value  of this BigDecimal, with rounding according to the  context settings. |
|`add(${1:BigDecimal}, ${2:MathContext})`|add|Takes 2 args. Method in class java.math.BigDecimal  Returns a BigDecimal whose value is (this + augend),  with rounding according to the context settings. |
|`abs()`|abs|Takes 0 args. Method in class java.math.BigInteger  Returns a BigInteger whose value is the absolute value of this  BigInteger. |
|`add()`|add|Takes 0 args. Method in class java.math.BigInteger  Returns a BigInteger whose value is (this + val). |
|`and()`|and|Takes 0 args. Method in class java.math.BigInteger  Returns a BigInteger whose value is (this &amp; val). |
|`andNot()`|andNot|Takes 0 args. Method in class java.math.BigInteger  Returns a BigInteger whose value is (this &amp; ~val). |
|`abort()`|abort|Takes 0 args. Method in class java.net.CacheRequest  Aborts the attempt to cache the response. |
|`ACCEPT_ALL`|ACCEPT_ALL|Takes 0 args. Static variable in interface java.net.CookiePolicy  One pre-defined policy which accepts all cookies. |
|`ACCEPT_NONE`|ACCEPT_NONE|Takes 0 args. Static variable in interface java.net.CookiePolicy  One pre-defined policy which accepts no cookies. |
|`ACCEPT_ORIGINAL_SERVER`|ACCEPT_ORIGINAL_SERVER|Takes 0 args. Static variable in interface java.net.CookiePolicy  One pre-defined policy which only accepts cookies from original server. |
|`add(${1:URI}, ${2:HttpCookie})`|add|Takes 2 args. Method in interface java.net.CookieStore  Adds one HTTP cookie to the store. |
|`ALLOW_UNASSIGNED`|ALLOW_UNASSIGNED|Takes 0 args. Static variable in class java.net.IDN  Flag to allow processing of unassigned code points |
|`address()`|address|Takes 0 args. Method in class java.net.Proxy  Returns the socket address of the proxy, or  null if its a direct connection. |
|`accept()`|accept|Takes 0 args. Method in class java.net.ServerSocket  Listens for a connection to be made to this socket and accepts  it. |
|`accept()`|accept|Takes 0 args. Method in class java.net.SocketImpl  Accepts a connection. |
|`address`|address|Takes 0 args. Variable in class java.net.SocketImpl  The IP address of the remote end of this socket. |
|`available()`|available|Takes 0 args. Method in class java.net.SocketImpl  Returns the number of bytes that can be read from this socket  without blocking. |
|`addURL()`|addURL|Takes 0 args. Method in class java.net.URLClassLoader  Appends the specified URL to the list of URLs to search for  classes and resources. |
|`addRequestProperty(${1:String}, ${2:String})`|addRequestProperty|Takes 2 args. Method in class java.net.URLConnection  Adds a general request property specified by a  key-value pair. |
|`allowUserInteraction`|allowUserInteraction|Takes 0 args. Variable in class java.net.URLConnection  If true, this URL is being examined in  a context in which it makes sense to allow user interactions such  as popping up an authentication dialog. |
|`array()`|array|Takes 0 args. Method in class java.nio.Buffer  Returns the array that backs this  buffer  (optional operation). |
|`arrayOffset()`|arrayOffset|Takes 0 args. Method in class java.nio.Buffer  Returns the offset within this buffer's backing array of the first  element of the buffer  (optional operation). |
|`allocate()`|allocate|Takes 0 args. Static method in class java.nio.ByteBuffer  Allocates a new byte buffer. |
|`allocateDirect()`|allocateDirect|Takes 0 args. Static method in class java.nio.ByteBuffer  Allocates a new direct byte buffer. |
|`array()`|array|Takes 0 args. Method in class java.nio.ByteBuffer  Returns the byte array that backs this  buffer  (optional operation). |
|`arrayOffset()`|arrayOffset|Takes 0 args. Method in class java.nio.ByteBuffer  Returns the offset within this buffer's backing array of the first  element of the buffer  (optional operation). |
|`asCharBuffer()`|asCharBuffer|Takes 0 args. Method in class java.nio.ByteBuffer  Creates a view of this byte buffer as a char buffer. |
|`asDoubleBuffer()`|asDoubleBuffer|Takes 0 args. Method in class java.nio.ByteBuffer  Creates a view of this byte buffer as a double buffer. |
|`asFloatBuffer()`|asFloatBuffer|Takes 0 args. Method in class java.nio.ByteBuffer  Creates a view of this byte buffer as a float buffer. |
|`asIntBuffer()`|asIntBuffer|Takes 0 args. Method in class java.nio.ByteBuffer  Creates a view of this byte buffer as an int buffer. |
|`asLongBuffer()`|asLongBuffer|Takes 0 args. Method in class java.nio.ByteBuffer  Creates a view of this byte buffer as a long buffer. |
|`asReadOnlyBuffer()`|asReadOnlyBuffer|Takes 0 args. Method in class java.nio.ByteBuffer  Creates a new, read-only byte buffer that shares this buffer's  content. |
|`asShortBuffer()`|asShortBuffer|Takes 0 args. Method in class java.nio.ByteBuffer  Creates a view of this byte buffer as a short buffer. |
|`allocate()`|allocate|Takes 0 args. Static method in class java.nio.CharBuffer  Allocates a new char buffer. |
|`append(${1:CharSequence}, ${2:int}, ${3:int})`|append|Takes 3 args. Method in class java.nio.CharBuffer  Appends a subsequence of the  specified character sequence  to this  buffer  (optional operation). |
|`array()`|array|Takes 0 args. Method in class java.nio.CharBuffer  Returns the char array that backs this  buffer  (optional operation). |
|`arrayOffset()`|arrayOffset|Takes 0 args. Method in class java.nio.CharBuffer  Returns the offset within this buffer's backing array of the first  element of the buffer  (optional operation). |
|`asReadOnlyBuffer()`|asReadOnlyBuffer|Takes 0 args. Method in class java.nio.CharBuffer  Creates a new, read-only char buffer that shares this buffer's  content. |
|`allocate()`|allocate|Takes 0 args. Static method in class java.nio.DoubleBuffer  Allocates a new double buffer. |
|`array()`|array|Takes 0 args. Method in class java.nio.DoubleBuffer  Returns the double array that backs this  buffer  (optional operation). |
|`arrayOffset()`|arrayOffset|Takes 0 args. Method in class java.nio.DoubleBuffer  Returns the offset within this buffer's backing array of the first  element of the buffer  (optional operation). |
|`asReadOnlyBuffer()`|asReadOnlyBuffer|Takes 0 args. Method in class java.nio.DoubleBuffer  Creates a new, read-only double buffer that shares this buffer's  content. |
|`allocate()`|allocate|Takes 0 args. Static method in class java.nio.FloatBuffer  Allocates a new float buffer. |
|`array()`|array|Takes 0 args. Method in class java.nio.FloatBuffer  Returns the float array that backs this  buffer  (optional operation). |
|`arrayOffset()`|arrayOffset|Takes 0 args. Method in class java.nio.FloatBuffer  Returns the offset within this buffer's backing array of the first  element of the buffer  (optional operation). |
|`asReadOnlyBuffer()`|asReadOnlyBuffer|Takes 0 args. Method in class java.nio.FloatBuffer  Creates a new, read-only float buffer that shares this buffer's  content. |
|`allocate()`|allocate|Takes 0 args. Static method in class java.nio.IntBuffer  Allocates a new int buffer. |
|`array()`|array|Takes 0 args. Method in class java.nio.IntBuffer  Returns the int array that backs this  buffer  (optional operation). |
|`arrayOffset()`|arrayOffset|Takes 0 args. Method in class java.nio.IntBuffer  Returns the offset within this buffer's backing array of the first  element of the buffer  (optional operation). |
|`asReadOnlyBuffer()`|asReadOnlyBuffer|Takes 0 args. Method in class java.nio.IntBuffer  Creates a new, read-only int buffer that shares this buffer's  content. |
|`allocate()`|allocate|Takes 0 args. Static method in class java.nio.LongBuffer  Allocates a new long buffer. |
|`array()`|array|Takes 0 args. Method in class java.nio.LongBuffer  Returns the long array that backs this  buffer  (optional operation). |
|`arrayOffset()`|arrayOffset|Takes 0 args. Method in class java.nio.LongBuffer  Returns the offset within this buffer's backing array of the first  element of the buffer  (optional operation). |
|`asReadOnlyBuffer()`|asReadOnlyBuffer|Takes 0 args. Method in class java.nio.LongBuffer  Creates a new, read-only long buffer that shares this buffer's  content. |
|`allocate()`|allocate|Takes 0 args. Static method in class java.nio.ShortBuffer  Allocates a new short buffer. |
|`array()`|array|Takes 0 args. Method in class java.nio.ShortBuffer  Returns the short array that backs this  buffer  (optional operation). |
|`arrayOffset()`|arrayOffset|Takes 0 args. Method in class java.nio.ShortBuffer  Returns the offset within this buffer's backing array of the first  element of the buffer  (optional operation). |
|`asReadOnlyBuffer()`|asReadOnlyBuffer|Takes 0 args. Method in class java.nio.ShortBuffer  Creates a new, read-only short buffer that shares this buffer's  content. |
|`awaitTermination(${1:long}, ${2:TimeUnit})`|awaitTermination|Takes 2 args. Method in class java.nio.channels.AsynchronousChannelGroup  Awaits termination of the group. |
|`accept(${1:A}, ${2:CompletionHandler})`|accept|Takes 2 args. Method in class java.nio.channels.AsynchronousServerSocketChannel  Accepts a connection. |
|`acquiredBy()`|acquiredBy|Takes 0 args. Method in class java.nio.channels.FileLock  Returns the channel upon whose file this lock was acquired. |
|`attach()`|attach|Takes 0 args. Method in class java.nio.channels.SelectionKey  Attaches the given object to this key. |
|`attachment()`|attachment|Takes 0 args. Method in class java.nio.channels.SelectionKey  Retrieves the current attachment. |
|`accept()`|accept|Takes 0 args. Method in class java.nio.channels.ServerSocketChannel  Accepts a connection made to this channel's socket. |
|`aliases()`|aliases|Takes 0 args. Method in class java.nio.charset.Charset  Returns a set containing this charset's aliases. |
|`availableCharsets()`|availableCharsets|Takes 0 args. Static method in class java.nio.charset.Charset  Constructs a sorted map from canonical charset names to charset objects. |
|`averageCharsPerByte()`|averageCharsPerByte|Takes 0 args. Method in class java.nio.charset.CharsetDecoder  Returns the average number of characters that will be produced for each  byte of input. |
|`averageBytesPerChar()`|averageBytesPerChar|Takes 0 args. Method in class java.nio.charset.CharsetEncoder  Returns the average number of bytes that will be produced for each  character of input. |
|`accept()`|accept|Takes 0 args. Method in interface java.nio.file.DirectoryStream.Filter  Decides if the given directory entry should be accepted or filtered. |
|`ADD_FILE`|ADD_FILE|Takes 0 args. Static variable in enum java.nio.file.attribute.AclEntryPermission  Permission to add a new file to a directory (equal to AclEntryPermission.WRITE_DATA) |
|`ADD_SUBDIRECTORY`|ADD_SUBDIRECTORY|Takes 0 args. Static variable in enum java.nio.file.attribute.AclEntryPermission  Permission to create a subdirectory to a directory (equal to AclEntryPermission.APPEND_DATA) |
|`asFileAttribute()`|asFileAttribute|Takes 0 args. Static method in class java.nio.file.attribute.PosixFilePermissions  Creates a FileAttribute, encapsulating a copy of the given file  permissions, suitable for passing to the createFile or createDirectory  methods. |
|`activeObject(${1:ActivationID}, ${2:Remote})`|activeObject|Takes 2 args. Method in class java.rmi.activation.ActivationGroup  The group's activeObject method is called when an  object is exported (either by Activatable object  construction or an explicit call to  Activatable.exportObject. |
|`activate()`|activate|Takes 0 args. Method in class java.rmi.activation.ActivationID  Activate the object for this id. |
|`activeObject(${1:ActivationID}, ${2:MarshalledObject})`|activeObject|Takes 2 args. Method in interface java.rmi.activation.ActivationMonitor  Informs that an object is now active. |
|`activeGroup(${1:ActivationGroupID}, ${2:ActivationInstantiator}, ${3:long})`|activeGroup|Takes 3 args. Method in interface java.rmi.activation.ActivationSystem  Callback to inform activation system that group is now  active. |
|`activate(${1:ActivationID}, ${2:boolean})`|activate|Takes 2 args. Method in interface java.rmi.activation.Activator  Activate the object associated with the activation identifier,  id. |
|`ACTIVATOR_ID`|ACTIVATOR_ID|Takes 0 args. Static variable in class java.rmi.server.ObjID  Object number for well-known ObjID of the activator. |
|`aliases()`|aliases|Takes 0 args. Method in class java.security.KeyStore  Lists all the alias names of this keystore. |
|`add()`|add|Takes 0 args. Method in class java.security.PermissionCollection  Adds a permission object to the current collection of permission objects. |
|`add()`|add|Takes 0 args. Method in class java.security.Permissions  Adds a permission object to the PermissionCollection for the class the  permission belongs to. |
|`addProvider()`|addProvider|Takes 0 args. Static method in class java.security.Security  Adds a provider to the next position available. |
|`appRandom`|appRandom|Takes 0 args. Variable in class java.security.SignatureSpi  Application-specified source of randomness. |
|`addEntry(${1:Principal}, ${2:AclEntry})`|addEntry|Takes 2 args. Method in interface java.security.acl.Acl  Adds an ACL entry to this ACL. |
|`addPermission()`|addPermission|Takes 0 args. Method in interface java.security.acl.AclEntry  Adds the specified permission to this ACL entry. |
|`addMember()`|addMember|Takes 0 args. Method in interface java.security.acl.Group  Adds the specified member to the group. |
|`addOwner(${1:Principal}, ${2:Principal})`|addOwner|Takes 2 args. Method in interface java.security.acl.Owner  Adds an owner. |
|`addCertPathChecker()`|addCertPathChecker|Takes 0 args. Method in class java.security.cert.PKIXParameters  Adds a PKIXCertPathChecker to the list of certification  path checkers. |
|`addCertStore()`|addCertStore|Takes 0 args. Method in class java.security.cert.PKIXParameters  Adds a CertStore to the end of the list of  CertStores used in finding certificates and CRLs. |
|`addIssuer()`|addIssuer|Takes 0 args. Method in class java.security.cert.X509CRLSelector  Adds a name to the issuerNames criterion. |
|`addIssuerName()`|addIssuerName|Takes 0 args. Method in class java.security.cert.X509CRLSelector  Denigrated, use  X509CRLSelector.addIssuer(X500Principal) or  X509CRLSelector.addIssuerName(byte[]) instead. |
|`addPathToName(${1:int}, ${2:String})`|addPathToName|Takes 2 args. Method in class java.security.cert.X509CertSelector  Adds a name to the pathToNames criterion. |
|`addSubjectAlternativeName(${1:int}, ${2:String})`|addSubjectAlternativeName|Takes 2 args. Method in class java.security.cert.X509CertSelector  Adds a name to the subjectAlternativeNames criterion. |
|`abort()`|abort|Takes 0 args. Method in interface java.sql.Connection  Terminates an open connection. |
|`allProceduresAreCallable()`|allProceduresAreCallable|Takes 0 args. Method in interface java.sql.DatabaseMetaData  Retrieves whether the current user can call all the procedures  returned by the method getProcedures. |
|`allTablesAreSelectable()`|allTablesAreSelectable|Takes 0 args. Method in interface java.sql.DatabaseMetaData  Retrieves whether the current user can use all the tables returned  by the method getTables in a SELECT  statement. |
|`attributeNoNulls`|attributeNoNulls|Takes 0 args. Static variable in interface java.sql.DatabaseMetaData  Indicates that NULL values might not be allowed. |
|`attributeNullable`|attributeNullable|Takes 0 args. Static variable in interface java.sql.DatabaseMetaData  Indicates that NULL values are definitely allowed. |
|`attributeNullableUnknown`|attributeNullableUnknown|Takes 0 args. Static variable in interface java.sql.DatabaseMetaData  Indicates that whether NULL values are allowed is not  known. |
|`autoCommitFailureClosesAllResultSets()`|autoCommitFailureClosesAllResultSets|Takes 0 args. Method in interface java.sql.DatabaseMetaData  Retrieves whether a SQLException while autoCommit is true inidcates  that all open ResultSets are closed, even ones that are holdable. |
|`acceptsURL()`|acceptsURL|Takes 0 args. Method in interface java.sql.Driver  Retrieves whether the driver thinks that it can open a connection  to the given URL. |
|`addBatch()`|addBatch|Takes 0 args. Method in interface java.sql.PreparedStatement  Adds a set of parameters to this PreparedStatement  object's batch of commands. |
|`absolute()`|absolute|Takes 0 args. Method in interface java.sql.ResultSet  Moves the cursor to the given row number in  this ResultSet object. |
|`afterLast()`|afterLast|Takes 0 args. Method in interface java.sql.ResultSet  Moves the cursor to the end of  this ResultSet object, just after the  last row. |
|`addBatch()`|addBatch|Takes 0 args. Method in interface java.sql.Statement  Adds the given SQL command to the current list of commmands for this  Statement object. |
|`after()`|after|Takes 0 args. Method in class java.sql.Timestamp  Indicates whether this Timestamp object is  later than the given Timestamp object. |
|`ARRAY`|ARRAY|Takes 0 args. Static variable in class java.sql.Types  The constant in the Java programming language, sometimes referred to  as a type code, that identifies the generic SQL type  ARRAY. |
|`addAttribute(${1:AttributedCharacterIterator.Attribute}, ${2:Object}, ${3:int}, ${4:int})`|addAttribute|Takes 4 args. Method in class java.text.AttributedString  Adds an attribute to a subrange of the string. |
|`addAttributes(${1:Map}, ${2:int}, ${3:int})`|addAttributes|Takes 3 args. Method in class java.text.AttributedString  Adds a set of attributes to a subrange of the string. |
|`applyPattern()`|applyPattern|Takes 0 args. Method in class java.text.ChoiceFormat  Sets the pattern. |
|`AM_PM`|AM_PM|Takes 0 args. Static variable in class java.text.DateFormat.Field  Constant identifying the time of day indicator  (e.g. |
|`AM_PM_FIELD`|AM_PM_FIELD|Takes 0 args. Static variable in class java.text.DateFormat  Useful constant for AM_PM field alignment. |
|`applyLocalizedPattern()`|applyLocalizedPattern|Takes 0 args. Method in class java.text.DecimalFormat  Apply the given pattern to this Format object. |
|`applyPattern()`|applyPattern|Takes 0 args. Method in class java.text.DecimalFormat  Apply the given pattern to this Format object. |
|`ARGUMENT`|ARGUMENT|Takes 0 args. Static variable in class java.text.MessageFormat.Field  Constant identifying a portion of a message that was generated  from an argument passed into formatToCharacterIterator. |
|`applyPattern()`|applyPattern|Takes 0 args. Method in class java.text.MessageFormat  Sets the pattern used by this message format. |
|`applyLocalizedPattern()`|applyLocalizedPattern|Takes 0 args. Method in class java.text.SimpleDateFormat  Applies the given localized pattern string to this date format. |
|`applyPattern()`|applyPattern|Takes 0 args. Method in class java.text.SimpleDateFormat  Applies the given pattern string to this date format. |
|`add()`|add|Takes 0 args. Method in class java.util.AbstractCollection  Ensures that this collection contains the specified element (optional  operation). |
|`addAll()`|addAll|Takes 0 args. Method in class java.util.AbstractCollection  Adds all of the elements in the specified collection to this collection  (optional operation). |
|`add(${1:int}, ${2:E})`|add|Takes 2 args. Method in class java.util.AbstractList  Inserts the specified element at the specified position in this list  (optional operation). |
|`addAll(${1:int}, ${2:Collection})`|addAll|Takes 2 args. Method in class java.util.AbstractList  Inserts all of the elements in the specified collection into this  list at the specified position (optional operation). |
|`add()`|add|Takes 0 args. Method in class java.util.AbstractQueue  Inserts the specified element into this queue if it is possible to do so  immediately without violating capacity restrictions, returning  true upon success and throwing an IllegalStateException  if no space is currently available. |
|`addAll()`|addAll|Takes 0 args. Method in class java.util.AbstractQueue  Adds all of the elements in the specified collection to this  queue. |
|`add(${1:int}, ${2:E})`|add|Takes 2 args. Method in class java.util.AbstractSequentialList  Inserts the specified element at the specified position in this list  (optional operation). |
|`addAll(${1:int}, ${2:Collection})`|addAll|Takes 2 args. Method in class java.util.AbstractSequentialList  Inserts all of the elements in the specified collection into this  list at the specified position (optional operation). |
|`add()`|add|Takes 0 args. Method in class java.util.ArrayDeque  Inserts the specified element at the end of this deque. |
|`addFirst()`|addFirst|Takes 0 args. Method in class java.util.ArrayDeque  Inserts the specified element at the front of this deque. |
|`addLast()`|addLast|Takes 0 args. Method in class java.util.ArrayDeque  Inserts the specified element at the end of this deque. |
|`add(${1:int}, ${2:E})`|add|Takes 2 args. Method in class java.util.ArrayList  Inserts the specified element at the specified position in this  list. |
|`addAll()`|addAll|Takes 0 args. Method in class java.util.ArrayList  Appends all of the elements in the specified collection to the end of  this list, in the order that they are returned by the  specified collection's Iterator. |
|`asList()`|asList|Takes 0 args. Static method in class java.util.Arrays  Returns a fixed-size list backed by the specified array. |
|`and()`|and|Takes 0 args. Method in class java.util.BitSet  Performs a logical AND of this target bit set with the  argument bit set. |
|`andNot()`|andNot|Takes 0 args. Method in class java.util.BitSet  Clears all of the bits in this BitSet whose corresponding  bit is set in the specified BitSet. |
|`ALL_STYLES`|ALL_STYLES|Takes 0 args. Static variable in class java.util.Calendar  A style specifier for getDisplayNames indicating names in all styles, such as  "January" and "Jan". |
|`AM`|AM|Takes 0 args. Static variable in class java.util.Calendar  Value of the Calendar.AM_PM field indicating the  period of the day from midnight to just before noon. |
|`AM_PM`|AM_PM|Takes 0 args. Static variable in class java.util.Calendar  Field number for get and set indicating  whether the HOUR is before or after noon. |
|`APRIL`|APRIL|Takes 0 args. Static variable in class java.util.Calendar  Value of the Calendar.MONTH field indicating the  fourth month of the year in the Gregorian and Julian calendars. |
|`AUGUST`|AUGUST|Takes 0 args. Static variable in class java.util.Calendar  Value of the Calendar.MONTH field indicating the  eighth month of the year in the Gregorian and Julian calendars. |
|`add(${1:int}, ${2:int})`|add|Takes 2 args. Method in class java.util.Calendar  Adds or subtracts the specified amount of time to the given calendar field,  based on the calendar's rules. |
|`after()`|after|Takes 0 args. Method in class java.util.Calendar  Returns whether this Calendar represents a time  after the time represented by the specified  Object. |
|`areFieldsSet`|areFieldsSet|Takes 0 args. Variable in class java.util.Calendar  True if fields[] are in sync with the currently set time. |
|`add()`|add|Takes 0 args. Method in interface java.util.Collection  Ensures that this collection contains the specified element (optional  operation). |
|`addAll()`|addAll|Takes 0 args. Method in interface java.util.Collection  Adds all of the elements in the specified collection to this collection  (optional operation). |
|`addAll(${1:Collection}, ${2:T...})`|addAll|Takes 2 args. Static method in class java.util.Collections  Adds all of the specified elements to the specified collection. |
|`asLifoQueue()`|asLifoQueue|Takes 0 args. Static method in class java.util.Collections  Returns a view of a Deque as a Last-in-first-out (Lifo)  Queue. |
|`after()`|after|Takes 0 args. Method in class java.util.Date  Tests if this date is after the specified date. |
|`add()`|add|Takes 0 args. Method in interface java.util.Deque  Inserts the specified element into the queue represented by this deque  (in other words, at the tail of this deque) if it is possible to do so  immediately without violating capacity restrictions, returning  true upon success and throwing an  IllegalStateException if no space is currently available. |
|`addFirst()`|addFirst|Takes 0 args. Method in interface java.util.Deque  Inserts the specified element at the front of this deque if it is  possible to do so immediately without violating capacity restrictions. |
|`addLast()`|addLast|Takes 0 args. Method in interface java.util.Deque  Inserts the specified element at the end of this deque if it is  possible to do so immediately without violating capacity restrictions. |
|`allOf()`|allOf|Takes 0 args. Static method in class java.util.EnumSet  Creates an enum set containing all of the elements in the specified  element type. |
|`ALTERNATE`|ALTERNATE|Takes 0 args. Static variable in class java.util.FormattableFlags  Requires the output to use an alternate form. |
|`AD`|AD|Takes 0 args. Static variable in class java.util.GregorianCalendar  Value of the ERA field indicating  the common era (Anno Domini), also known as CE. |
|`add(${1:int}, ${2:int})`|add|Takes 2 args. Method in class java.util.GregorianCalendar  Adds the specified (signed) amount of time to the given calendar field,  based on the calendar's rules. |
|`add()`|add|Takes 0 args. Method in class java.util.HashSet  Adds the specified element to this set if it is not already present. |
|`add(${1:int}, ${2:E})`|add|Takes 2 args. Method in class java.util.LinkedList  Inserts the specified element at the specified position in this list. |
|`addAll()`|addAll|Takes 0 args. Method in class java.util.LinkedList  Appends all of the elements in the specified collection to the end of  this list, in the order that they are returned by the specified  collection's iterator. |
|`addFirst()`|addFirst|Takes 0 args. Method in class java.util.LinkedList  Inserts the specified element at the beginning of this list. |
|`addLast()`|addLast|Takes 0 args. Method in class java.util.LinkedList  Appends the specified element to the end of this list. |
|`add(${1:int}, ${2:E})`|add|Takes 2 args. Method in interface java.util.List  Inserts the specified element at the specified position in this list  (optional operation). |
|`addAll()`|addAll|Takes 0 args. Method in interface java.util.List  Appends all of the elements in the specified collection to the end of  this list, in the order that they are returned by the specified  collection's iterator (optional operation). |
|`add()`|add|Takes 0 args. Method in interface java.util.ListIterator  Inserts the specified element into the list (optional operation). |
|`addUnicodeLocaleAttribute()`|addUnicodeLocaleAttribute|Takes 0 args. Method in class java.util.Locale.Builder  Adds a unicode locale attribute, if not already present, otherwise  has no effect. |
|`addObserver()`|addObserver|Takes 0 args. Method in class java.util.Observable  Adds an observer to the set of observers for this object, provided  that it is not the same as some observer already in the set. |
|`add()`|add|Takes 0 args. Method in class java.util.PriorityQueue  Inserts the specified element into this priority queue. |
|`add()`|add|Takes 0 args. Method in interface java.util.Queue  Inserts the specified element into this queue if it is possible to do so  immediately without violating capacity restrictions, returning  true upon success and throwing an IllegalStateException  if no space is currently available. |
|`add()`|add|Takes 0 args. Method in interface java.util.Set  Adds the specified element to this set if it is not already present  (optional operation). |
|`addAll()`|addAll|Takes 0 args. Method in interface java.util.Set  Adds all of the elements in the specified collection to this set if  they're not already present (optional operation). |
|`add()`|add|Takes 0 args. Method in class java.util.TreeSet  Adds the specified element to this set if it is not already present. |
|`addAll()`|addAll|Takes 0 args. Method in class java.util.TreeSet  Adds all of the elements in the specified collection to this set. |
|`add(${1:int}, ${2:E})`|add|Takes 2 args. Method in class java.util.Vector  Inserts the specified element at the specified position in this Vector. |
|`addAll()`|addAll|Takes 0 args. Method in class java.util.Vector  Appends all of the elements in the specified Collection to the end of  this Vector, in the order that they are returned by the specified  Collection's Iterator. |
|`addElement()`|addElement|Takes 0 args. Method in class java.util.Vector  Adds the specified component to the end of this vector,  increasing its size by one. |
|`add()`|add|Takes 0 args. Method in class java.util.concurrent.ArrayBlockingQueue  Inserts the specified element at the tail of this queue if it is  possible to do so immediately without exceeding the queue's capacity,  returning true upon success and throwing an  IllegalStateException if this queue is full. |
|`add()`|add|Takes 0 args. Method in interface java.util.concurrent.BlockingDeque  Inserts the specified element into the queue represented by this deque  (in other words, at the tail of this deque) if it is possible to do so  immediately without violating capacity restrictions, returning  true upon success and throwing an  IllegalStateException if no space is currently available. |
|`addFirst()`|addFirst|Takes 0 args. Method in interface java.util.concurrent.BlockingDeque  Inserts the specified element at the front of this deque if it is  possible to do so immediately without violating capacity restrictions,  throwing an IllegalStateException if no space is currently  available. |
|`addLast()`|addLast|Takes 0 args. Method in interface java.util.concurrent.BlockingDeque  Inserts the specified element at the end of this deque if it is  possible to do so immediately without violating capacity restrictions,  throwing an IllegalStateException if no space is currently  available. |
|`add()`|add|Takes 0 args. Method in interface java.util.concurrent.BlockingQueue  Inserts the specified element into this queue if it is possible to do  so immediately without violating capacity restrictions, returning  true upon success and throwing an  IllegalStateException if no space is currently available. |
|`add()`|add|Takes 0 args. Method in class java.util.concurrent.ConcurrentLinkedDeque  Inserts the specified element at the tail of this deque. |
|`addAll()`|addAll|Takes 0 args. Method in class java.util.concurrent.ConcurrentLinkedDeque  Appends all of the elements in the specified collection to the end of  this deque, in the order that they are returned by the specified  collection's iterator. |
|`addFirst()`|addFirst|Takes 0 args. Method in class java.util.concurrent.ConcurrentLinkedDeque  Inserts the specified element at the front of this deque. |
|`addLast()`|addLast|Takes 0 args. Method in class java.util.concurrent.ConcurrentLinkedDeque  Inserts the specified element at the end of this deque. |
|`add()`|add|Takes 0 args. Method in class java.util.concurrent.ConcurrentLinkedQueue  Inserts the specified element at the tail of this queue. |
|`addAll()`|addAll|Takes 0 args. Method in class java.util.concurrent.ConcurrentLinkedQueue  Appends all of the elements in the specified collection to the end of  this queue, in the order that they are returned by the specified  collection's iterator. |
|`add()`|add|Takes 0 args. Method in class java.util.concurrent.ConcurrentSkipListSet  Adds the specified element to this set if it is not already present. |
|`add(${1:int}, ${2:E})`|add|Takes 2 args. Method in class java.util.concurrent.CopyOnWriteArrayList  Inserts the specified element at the specified position in this  list. |
|`addAll()`|addAll|Takes 0 args. Method in class java.util.concurrent.CopyOnWriteArrayList  Appends all of the elements in the specified collection to the end  of this list, in the order that they are returned by the specified  collection's iterator. |
|`addAllAbsent()`|addAllAbsent|Takes 0 args. Method in class java.util.concurrent.CopyOnWriteArrayList  Appends all of the elements in the specified collection that  are not already contained in this list, to the end of  this list, in the order that they are returned by the  specified collection's iterator. |
|`addIfAbsent()`|addIfAbsent|Takes 0 args. Method in class java.util.concurrent.CopyOnWriteArrayList  Append the element if not present. |
|`add()`|add|Takes 0 args. Method in class java.util.concurrent.CopyOnWriteArraySet  Adds the specified element to this set if it is not already present. |
|`addAll()`|addAll|Takes 0 args. Method in class java.util.concurrent.CopyOnWriteArraySet  Adds all of the elements in the specified collection to this set if  they're not already present. |
|`await(${1:long}, ${2:TimeUnit})`|await|Takes 2 args. Method in class java.util.concurrent.CountDownLatch  Causes the current thread to wait until the latch has counted down to  zero, unless the thread is interrupted,  or the specified waiting time elapses. |
|`await(${1:long}, ${2:TimeUnit})`|await|Takes 2 args. Method in class java.util.concurrent.CyclicBarrier  Waits until all parties have invoked  await on this barrier, or the specified waiting time elapses. |
|`add()`|add|Takes 0 args. Method in class java.util.concurrent.DelayQueue  Inserts the specified element into this delay queue. |
|`awaitTermination(${1:long}, ${2:TimeUnit})`|awaitTermination|Takes 2 args. Method in interface java.util.concurrent.ExecutorService  Blocks until all tasks have completed execution after a shutdown  request, or the timeout occurs, or the current thread is  interrupted, whichever happens first. |
|`awaitTermination(${1:long}, ${2:TimeUnit})`|awaitTermination|Takes 2 args. Method in class java.util.concurrent.ForkJoinPool  Blocks until all tasks have completed execution after a shutdown  request, or the timeout occurs, or the current thread is  interrupted, whichever happens first. |
|`adapt()`|adapt|Takes 0 args. Static method in class java.util.concurrent.ForkJoinTask  Returns a new ForkJoinTask that performs the call  method of the given Callable as its action, and returns  its result upon ForkJoinTask.join(), translating any checked exceptions  encountered into RuntimeException. |
|`add()`|add|Takes 0 args. Method in class java.util.concurrent.LinkedBlockingDeque  Inserts the specified element at the end of this deque unless it would  violate capacity restrictions. |
|`addFirst()`|addFirst|Takes 0 args. Method in class java.util.concurrent.LinkedBlockingDeque  |
|`addLast()`|addLast|Takes 0 args. Method in class java.util.concurrent.LinkedBlockingDeque  |
|`add()`|add|Takes 0 args. Method in class java.util.concurrent.LinkedTransferQueue  Inserts the specified element at the tail of this queue. |
|`arrive()`|arrive|Takes 0 args. Method in class java.util.concurrent.Phaser  Arrives at this phaser, without waiting for others to arrive. |
|`arriveAndAwaitAdvance()`|arriveAndAwaitAdvance|Takes 0 args. Method in class java.util.concurrent.Phaser  Arrives at this phaser and awaits others. |
|`arriveAndDeregister()`|arriveAndDeregister|Takes 0 args. Method in class java.util.concurrent.Phaser  Arrives at this phaser and deregisters from it without waiting  for others to arrive. |
|`awaitAdvance()`|awaitAdvance|Takes 0 args. Method in class java.util.concurrent.Phaser  Awaits the phase of this phaser to advance from the given phase  value, returning immediately if the current phase is not equal  to the given phase value or this phaser is terminated. |
|`awaitAdvanceInterruptibly(${1:int}, ${2:long}, ${3:TimeUnit})`|awaitAdvanceInterruptibly|Takes 3 args. Method in class java.util.concurrent.Phaser  Awaits the phase of this phaser to advance from the given phase  value or the given timeout to elapse, throwing InterruptedException if interrupted while waiting, or  returning immediately if the current phase is not equal to the  given phase value or this phaser is terminated. |
|`add()`|add|Takes 0 args. Method in class java.util.concurrent.PriorityBlockingQueue  Inserts the specified element into this priority queue. |
|`acquire()`|acquire|Takes 0 args. Method in class java.util.concurrent.Semaphore  Acquires the given number of permits from this semaphore,  blocking until all are available,  or the thread is interrupted. |
|`acquireUninterruptibly()`|acquireUninterruptibly|Takes 0 args. Method in class java.util.concurrent.Semaphore  Acquires the given number of permits from this semaphore,  blocking until all are available. |
|`availablePermits()`|availablePermits|Takes 0 args. Method in class java.util.concurrent.Semaphore  Returns the current number of permits available in this semaphore. |
|`afterExecute(${1:Runnable}, ${2:Throwable})`|afterExecute|Takes 2 args. Method in class java.util.concurrent.ThreadPoolExecutor  Method invoked upon completion of execution of the given Runnable. |
|`allowCoreThreadTimeOut()`|allowCoreThreadTimeOut|Takes 0 args. Method in class java.util.concurrent.ThreadPoolExecutor  Sets the policy governing whether core threads may time out and  terminate if no tasks arrive within the keep-alive time, being  replaced if needed when new tasks arrive. |
|`allowsCoreThreadTimeOut()`|allowsCoreThreadTimeOut|Takes 0 args. Method in class java.util.concurrent.ThreadPoolExecutor  Returns true if this pool allows core threads to time out and  terminate if no tasks arrive within the keepAlive time, being  replaced if needed when new tasks arrive. |
|`awaitTermination(${1:long}, ${2:TimeUnit})`|awaitTermination|Takes 2 args. Method in class java.util.concurrent.ThreadPoolExecutor  |
|`addAndGet()`|addAndGet|Takes 0 args. Method in class java.util.concurrent.atomic.AtomicInteger  Atomically adds the given value to the current value. |
|`addAndGet(${1:int}, ${2:int})`|addAndGet|Takes 2 args. Method in class java.util.concurrent.atomic.AtomicIntegerArray  Atomically adds the given value to the element at index i. |
|`addAndGet(${1:T}, ${2:int})`|addAndGet|Takes 2 args. Method in class java.util.concurrent.atomic.AtomicIntegerFieldUpdater  Atomically adds the given value to the current value of the field of  the given object managed by this updater. |
|`addAndGet()`|addAndGet|Takes 0 args. Method in class java.util.concurrent.atomic.AtomicLong  Atomically adds the given value to the current value. |
|`addAndGet(${1:int}, ${2:long})`|addAndGet|Takes 2 args. Method in class java.util.concurrent.atomic.AtomicLongArray  Atomically adds the given value to the element at index i. |
|`addAndGet(${1:T}, ${2:long})`|addAndGet|Takes 2 args. Method in class java.util.concurrent.atomic.AtomicLongFieldUpdater  Atomically adds the given value to the current value of the field of  the given object managed by this updater. |
|`attemptMark(${1:V}, ${2:boolean})`|attemptMark|Takes 2 args. Method in class java.util.concurrent.atomic.AtomicMarkableReference  Atomically sets the value of the mark to the given update value  if the current reference is == to the expected  reference. |
|`attemptStamp(${1:V}, ${2:int})`|attemptStamp|Takes 2 args. Method in class java.util.concurrent.atomic.AtomicStampedReference  Atomically sets the value of the stamp to the given update value  if the current reference is == to the expected  reference. |
|`await(${1:long}, ${2:TimeUnit})`|await|Takes 2 args. Method in class java.util.concurrent.locks.AbstractQueuedLongSynchronizer.ConditionObject  Implements timed condition wait. |
|`awaitNanos()`|awaitNanos|Takes 0 args. Method in class java.util.concurrent.locks.AbstractQueuedLongSynchronizer.ConditionObject  Implements timed condition wait. |
|`awaitUninterruptibly()`|awaitUninterruptibly|Takes 0 args. Method in class java.util.concurrent.locks.AbstractQueuedLongSynchronizer.ConditionObject  Implements uninterruptible condition wait. |
|`awaitUntil()`|awaitUntil|Takes 0 args. Method in class java.util.concurrent.locks.AbstractQueuedLongSynchronizer.ConditionObject  Implements absolute timed condition wait. |
|`acquire()`|acquire|Takes 0 args. Method in class java.util.concurrent.locks.AbstractQueuedLongSynchronizer  Acquires in exclusive mode, ignoring interrupts. |
|`acquireInterruptibly()`|acquireInterruptibly|Takes 0 args. Method in class java.util.concurrent.locks.AbstractQueuedLongSynchronizer  Acquires in exclusive mode, aborting if interrupted. |
|`acquireShared()`|acquireShared|Takes 0 args. Method in class java.util.concurrent.locks.AbstractQueuedLongSynchronizer  Acquires in shared mode, ignoring interrupts. |
|`acquireSharedInterruptibly()`|acquireSharedInterruptibly|Takes 0 args. Method in class java.util.concurrent.locks.AbstractQueuedLongSynchronizer  Acquires in shared mode, aborting if interrupted. |
|`await(${1:long}, ${2:TimeUnit})`|await|Takes 2 args. Method in class java.util.concurrent.locks.AbstractQueuedSynchronizer.ConditionObject  Implements timed condition wait. |
|`awaitNanos()`|awaitNanos|Takes 0 args. Method in class java.util.concurrent.locks.AbstractQueuedSynchronizer.ConditionObject  Implements timed condition wait. |
|`awaitUninterruptibly()`|awaitUninterruptibly|Takes 0 args. Method in class java.util.concurrent.locks.AbstractQueuedSynchronizer.ConditionObject  Implements uninterruptible condition wait. |
|`awaitUntil()`|awaitUntil|Takes 0 args. Method in class java.util.concurrent.locks.AbstractQueuedSynchronizer.ConditionObject  Implements absolute timed condition wait. |
|`acquire()`|acquire|Takes 0 args. Method in class java.util.concurrent.locks.AbstractQueuedSynchronizer  Acquires in exclusive mode, ignoring interrupts. |
|`acquireInterruptibly()`|acquireInterruptibly|Takes 0 args. Method in class java.util.concurrent.locks.AbstractQueuedSynchronizer  Acquires in exclusive mode, aborting if interrupted. |
|`acquireShared()`|acquireShared|Takes 0 args. Method in class java.util.concurrent.locks.AbstractQueuedSynchronizer  Acquires in shared mode, ignoring interrupts. |
|`acquireSharedInterruptibly()`|acquireSharedInterruptibly|Takes 0 args. Method in class java.util.concurrent.locks.AbstractQueuedSynchronizer  Acquires in shared mode, aborting if interrupted. |
|`await(${1:long}, ${2:TimeUnit})`|await|Takes 2 args. Method in interface java.util.concurrent.locks.Condition  Causes the current thread to wait until it is signalled or interrupted,  or the specified waiting time elapses. |
|`awaitNanos()`|awaitNanos|Takes 0 args. Method in interface java.util.concurrent.locks.Condition  Causes the current thread to wait until it is signalled or interrupted,  or the specified waiting time elapses. |
|`awaitUninterruptibly()`|awaitUninterruptibly|Takes 0 args. Method in interface java.util.concurrent.locks.Condition  Causes the current thread to wait until it is signalled. |
|`awaitUntil()`|awaitUntil|Takes 0 args. Method in interface java.util.concurrent.locks.Condition  Causes the current thread to wait until it is signalled or interrupted,  or the specified deadline elapses. |
|`addPropertyChangeListener()`|addPropertyChangeListener|Takes 0 args. Method in interface java.util.jar.Pack200.Packer  Registers a listener for PropertyChange events on the properties map. |
|`addPropertyChangeListener()`|addPropertyChangeListener|Takes 0 args. Method in interface java.util.jar.Pack200.Unpacker  Registers a listener for PropertyChange events on the properties map. |
|`ALL`|ALL|Takes 0 args. Static variable in class java.util.logging.Level  ALL indicates that all messages should be logged. |
|`addLogger()`|addLogger|Takes 0 args. Method in class java.util.logging.LogManager  Add a named logger. |
|`addPropertyChangeListener()`|addPropertyChangeListener|Takes 0 args. Method in class java.util.logging.LogManager  Adds an event listener to be invoked when the logging  properties are re-read. |
|`addHandler()`|addHandler|Takes 0 args. Method in class java.util.logging.Logger  Add a log Handler to receive logging messages. |
|`absolutePath()`|absolutePath|Takes 0 args. Method in class java.util.prefs.AbstractPreferences  Implements the absolutePath method as per the specification in  Preferences.absolutePath(). |
|`addNodeChangeListener()`|addNodeChangeListener|Takes 0 args. Method in class java.util.prefs.AbstractPreferences  |
|`addPreferenceChangeListener()`|addPreferenceChangeListener|Takes 0 args. Method in class java.util.prefs.AbstractPreferences  |
|`absolutePath()`|absolutePath|Takes 0 args. Method in class java.util.prefs.Preferences  Returns this preference node's absolute path name. |
|`addNodeChangeListener()`|addNodeChangeListener|Takes 0 args. Method in class java.util.prefs.Preferences  Registers the specified listener to receive node change events  for this node. |
|`addPreferenceChangeListener()`|addPreferenceChangeListener|Takes 0 args. Method in class java.util.prefs.Preferences  Registers the specified listener to receive preference change  events for this preference node. |
|`appendReplacement(${1:StringBuffer}, ${2:String})`|appendReplacement|Takes 2 args. Method in class java.util.regex.Matcher  Implements a non-terminal append-and-replace step. |
|`appendTail()`|appendTail|Takes 0 args. Method in class java.util.regex.Matcher  Implements a terminal append-and-replace step. |
|`available()`|available|Takes 0 args. Method in class java.util.zip.DeflaterInputStream  Returns 0 after EOF has been reached, otherwise always return 1. |
|`available()`|available|Takes 0 args. Method in class java.util.zip.InflaterInputStream  Returns 0 after EOF has been reached, otherwise always return 1. |
|`available()`|available|Takes 0 args. Method in class java.util.zip.ZipInputStream  Returns 0 after EOF has reached for the current entry data,  otherwise always return 1. |
|`attributes`|attributes|Takes 0 args. Variable in class javax.accessibility.AccessibleAttributeSequence  The text attributes |
|`addFocusListener()`|addFocusListener|Takes 0 args. Method in interface javax.accessibility.AccessibleComponent  Adds the specified focus listener to receive focus events from this  component. |
|`ACCESSIBLE_ACTION_PROPERTY`|ACCESSIBLE_ACTION_PROPERTY|Takes 0 args. Static variable in class javax.accessibility.AccessibleContext  Constant used to indicate that the supported set of actions  has changed. |
|`ACCESSIBLE_ACTIVE_DESCENDANT_PROPERTY`|ACCESSIBLE_ACTIVE_DESCENDANT_PROPERTY|Takes 0 args. Static variable in class javax.accessibility.AccessibleContext  Constant used to determine when the active descendant of a component  has changed. |
|`ACCESSIBLE_CARET_PROPERTY`|ACCESSIBLE_CARET_PROPERTY|Takes 0 args. Static variable in class javax.accessibility.AccessibleContext  Constant used to determine when the accessibleText caret has changed. |
|`ACCESSIBLE_CHILD_PROPERTY`|ACCESSIBLE_CHILD_PROPERTY|Takes 0 args. Static variable in class javax.accessibility.AccessibleContext  Constant used to determine when Accessible children are added/removed  from the object. |
|`ACCESSIBLE_COMPONENT_BOUNDS_CHANGED`|ACCESSIBLE_COMPONENT_BOUNDS_CHANGED|Takes 0 args. Static variable in class javax.accessibility.AccessibleContext  PropertyChangeEvent which indicates that a change has occurred  in a component's bounds. |
|`ACCESSIBLE_DESCRIPTION_PROPERTY`|ACCESSIBLE_DESCRIPTION_PROPERTY|Takes 0 args. Static variable in class javax.accessibility.AccessibleContext  Constant used to determine when the accessibleDescription property has  changed. |
|`ACCESSIBLE_HYPERTEXT_OFFSET`|ACCESSIBLE_HYPERTEXT_OFFSET|Takes 0 args. Static variable in class javax.accessibility.AccessibleContext  Constant used to indicate that a hypertext element has received focus. |
|`ACCESSIBLE_INVALIDATE_CHILDREN`|ACCESSIBLE_INVALIDATE_CHILDREN|Takes 0 args. Static variable in class javax.accessibility.AccessibleContext  PropertyChangeEvent which indicates that a significant change  has occurred to the children of a component like a tree or text. |
|`ACCESSIBLE_NAME_PROPERTY`|ACCESSIBLE_NAME_PROPERTY|Takes 0 args. Static variable in class javax.accessibility.AccessibleContext  Constant used to determine when the accessibleName property has  changed. |
|`ACCESSIBLE_SELECTION_PROPERTY`|ACCESSIBLE_SELECTION_PROPERTY|Takes 0 args. Static variable in class javax.accessibility.AccessibleContext  Constant used to determine when the accessibleSelection has changed. |
|`ACCESSIBLE_STATE_PROPERTY`|ACCESSIBLE_STATE_PROPERTY|Takes 0 args. Static variable in class javax.accessibility.AccessibleContext  Constant used to determine when the accessibleStateSet property has  changed. |
|`ACCESSIBLE_TABLE_CAPTION_CHANGED`|ACCESSIBLE_TABLE_CAPTION_CHANGED|Takes 0 args. Static variable in class javax.accessibility.AccessibleContext  Constant used to indicate that the table caption has changed  The old value in the PropertyChangeEvent will be an Accessible  representing the previous table caption and the new value will  be an Accessible representing the new table caption. |
|`ACCESSIBLE_TABLE_COLUMN_DESCRIPTION_CHANGED`|ACCESSIBLE_TABLE_COLUMN_DESCRIPTION_CHANGED|Takes 0 args. Static variable in class javax.accessibility.AccessibleContext  Constant used to indicate that the column description has changed  The old value in the PropertyChangeEvent will be null and the  new value will be an Integer representing the column index. |
|`ACCESSIBLE_TABLE_COLUMN_HEADER_CHANGED`|ACCESSIBLE_TABLE_COLUMN_HEADER_CHANGED|Takes 0 args. Static variable in class javax.accessibility.AccessibleContext  Constant used to indicate that the column header has changed  The old value in the PropertyChangeEvent will be null and the  new value will be an AccessibleTableModelChange representing  the header change. |
|`ACCESSIBLE_TABLE_MODEL_CHANGED`|ACCESSIBLE_TABLE_MODEL_CHANGED|Takes 0 args. Static variable in class javax.accessibility.AccessibleContext  Constant used to indicate that table data has changed. |
|`ACCESSIBLE_TABLE_ROW_DESCRIPTION_CHANGED`|ACCESSIBLE_TABLE_ROW_DESCRIPTION_CHANGED|Takes 0 args. Static variable in class javax.accessibility.AccessibleContext  Constant used to indicate that the row description has changed  The old value in the PropertyChangeEvent will be null and the  new value will be an Integer representing the row index. |
|`ACCESSIBLE_TABLE_ROW_HEADER_CHANGED`|ACCESSIBLE_TABLE_ROW_HEADER_CHANGED|Takes 0 args. Static variable in class javax.accessibility.AccessibleContext  Constant used to indicate that the row header has changed  The old value in the PropertyChangeEvent will be null and the  new value will be an AccessibleTableModelChange representing  the header change. |
|`ACCESSIBLE_TABLE_SUMMARY_CHANGED`|ACCESSIBLE_TABLE_SUMMARY_CHANGED|Takes 0 args. Static variable in class javax.accessibility.AccessibleContext  Constant used to indicate that the table summary has changed  The old value in the PropertyChangeEvent will be an Accessible  representing the previous table summary and the new value will  be an Accessible representing the new table summary. |
|`ACCESSIBLE_TEXT_ATTRIBUTES_CHANGED`|ACCESSIBLE_TEXT_ATTRIBUTES_CHANGED|Takes 0 args. Static variable in class javax.accessibility.AccessibleContext  PropertyChangeEvent which indicates that text attributes have changed. |
|`ACCESSIBLE_TEXT_PROPERTY`|ACCESSIBLE_TEXT_PROPERTY|Takes 0 args. Static variable in class javax.accessibility.AccessibleContext  PropertyChangeEvent which indicates that text has changed. |
|`ACCESSIBLE_VALUE_PROPERTY`|ACCESSIBLE_VALUE_PROPERTY|Takes 0 args. Static variable in class javax.accessibility.AccessibleContext  Constant used to determine when the accessibleValue property has  changed. |
|`ACCESSIBLE_VISIBLE_DATA_PROPERTY`|ACCESSIBLE_VISIBLE_DATA_PROPERTY|Takes 0 args. Static variable in class javax.accessibility.AccessibleContext  Constant used to determine when the visual appearance of the object  has changed. |
|`accessibleDescription`|accessibleDescription|Takes 0 args. Variable in class javax.accessibility.AccessibleContext  A localized String containing the description of the object. |
|`accessibleName`|accessibleName|Takes 0 args. Variable in class javax.accessibility.AccessibleContext  A localized String containing the name of the object. |
|`accessibleParent`|accessibleParent|Takes 0 args. Variable in class javax.accessibility.AccessibleContext  The accessible parent of this object. |
|`addPropertyChangeListener()`|addPropertyChangeListener|Takes 0 args. Method in class javax.accessibility.AccessibleContext  Adds a PropertyChangeListener to the listener list. |
|`ATTRIBUTE_RUN`|ATTRIBUTE_RUN|Takes 0 args. Static variable in interface javax.accessibility.AccessibleExtendedText  Constant used to indicate that the part of the text that should be  retrieved is contiguous text with the same text attributes. |
|`add()`|add|Takes 0 args. Method in class javax.accessibility.AccessibleRelationSet  Adds a new relation to the current relation set. |
|`addAll()`|addAll|Takes 0 args. Method in class javax.accessibility.AccessibleRelationSet  Adds all of the relations to the existing relation set. |
|`ALERT`|ALERT|Takes 0 args. Static variable in class javax.accessibility.AccessibleRole  Object is used to alert the user about something. |
|`AWT_COMPONENT`|AWT_COMPONENT|Takes 0 args. Static variable in class javax.accessibility.AccessibleRole  An AWT component, but nothing else is known about it. |
|`addAccessibleSelection()`|addAccessibleSelection|Takes 0 args. Method in interface javax.accessibility.AccessibleSelection  Adds the specified Accessible child of the object to the object's  selection. |
|`ACTIVE`|ACTIVE|Takes 0 args. Static variable in class javax.accessibility.AccessibleState  Indicates a window is currently the active window. |
|`ARMED`|ARMED|Takes 0 args. Static variable in class javax.accessibility.AccessibleState  Indicates that the object is armed. |
|`add()`|add|Takes 0 args. Method in class javax.accessibility.AccessibleStateSet  Adds a new state to the current state set if it is not already  present. |
|`addAll()`|addAll|Takes 0 args. Method in class javax.accessibility.AccessibleStateSet  Adds all of the states to the existing state set. |
|`addMailcap()`|addMailcap|Takes 0 args. Method in class javax.activation.MailcapCommandMap  Add entries to the registry. |
|`addMimeTypes()`|addMimeTypes|Takes 0 args. Method in class javax.activation.MimetypesFileTypeMap  Prepend the MIME type values to the registry. |
|`available()`|available|Takes 0 args. Method in class javax.crypto.CipherInputStream  Returns the number of bytes that can be read from this input  stream without blocking. |
|`activateController()`|activateController|Takes 0 args. Method in class javax.imageio.IIOParam  Activates the installed IIOParamController for  this IIOParam object and returns the resulting  value. |
|`activate()`|activate|Takes 0 args. Method in interface javax.imageio.IIOParamController  Activates the controller. |
|`abort()`|abort|Takes 0 args. Method in class javax.imageio.ImageReader  Requests that any current read operation be aborted. |
|`abortRequested()`|abortRequested|Takes 0 args. Method in class javax.imageio.ImageReader  Returns true if a request to abort the current  read operation has been made since the reader was instantiated or  clearAbortRequest was called. |
|`addIIOReadProgressListener()`|addIIOReadProgressListener|Takes 0 args. Method in class javax.imageio.ImageReader  Adds an IIOReadProgressListener to the list of  registered progress listeners. |
|`addIIOReadUpdateListener()`|addIIOReadUpdateListener|Takes 0 args. Method in class javax.imageio.ImageReader  Adds an IIOReadUpdateListener to the list of  registered update listeners. |
|`addIIOReadWarningListener()`|addIIOReadWarningListener|Takes 0 args. Method in class javax.imageio.ImageReader  Adds an IIOReadWarningListener to the list of  registered warning listeners. |
|`availableLocales`|availableLocales|Takes 0 args. Variable in class javax.imageio.ImageReader  An array of Locales which may be used to localize  warning messages, or null if localization is not  supported. |
|`abort()`|abort|Takes 0 args. Method in class javax.imageio.ImageWriter  Requests that any current write operation be aborted. |
|`abortRequested()`|abortRequested|Takes 0 args. Method in class javax.imageio.ImageWriter  Returns true if a request to abort the current  write operation has been made since the writer was instantiated or  clearAbortRequest was called. |
|`addIIOWriteProgressListener()`|addIIOWriteProgressListener|Takes 0 args. Method in class javax.imageio.ImageWriter  Adds an IIOWriteProgressListener to the list of  registered progress listeners. |
|`addIIOWriteWarningListener()`|addIIOWriteWarningListener|Takes 0 args. Method in class javax.imageio.ImageWriter  Adds an IIOWriteWarningListener to the list of  registered warning listeners. |
|`availableLocales`|availableLocales|Takes 0 args. Variable in class javax.imageio.ImageWriter  An array of Locales that may be used to localize  warning messages and compression setting values, or  null if localization is not supported. |
|`activateController()`|activateController|Takes 0 args. Method in class javax.imageio.metadata.IIOMetadata  Activates the installed IIOMetadataController for  this IIOMetadata object and returns the resulting  value. |
|`activate()`|activate|Takes 0 args. Method in interface javax.imageio.metadata.IIOMetadataController  Activates the controller. |
|`addAttribute(${1:String}, ${2:String}, ${3:int}, ${4:boolean}, ${5:String}, ${6:List})`|addAttribute|Takes 6 args. Method in class javax.imageio.metadata.IIOMetadataFormatImpl  Adds a new attribute to a previously defined element that will  be defined by a set of enumerated values. |
|`addBooleanAttribute(${1:String}, ${2:String}, ${3:boolean}, ${4:boolean})`|addBooleanAttribute|Takes 4 args. Method in class javax.imageio.metadata.IIOMetadataFormatImpl  Adds a new attribute to a previously defined element that will  be defined by the enumerated values TRUE and  FALSE, with a datatype of  DATATYPE_BOOLEAN. |
|`addChildElement(${1:String}, ${2:String})`|addChildElement|Takes 2 args. Method in class javax.imageio.metadata.IIOMetadataFormatImpl  Adds an existing element to the list of legal children for a  given parent node type. |
|`addElement(${1:String}, ${2:String}, ${3:int}, ${4:int})`|addElement|Takes 4 args. Method in class javax.imageio.metadata.IIOMetadataFormatImpl  Adds a new element type to this metadata document format with a  child policy of CHILD_POLICY_REPEAT. |
|`addObjectValue(${1:String}, ${2:Class}, ${3:int}, ${4:int})`|addObjectValue|Takes 4 args. Method in class javax.imageio.metadata.IIOMetadataFormatImpl  Allows an Object reference of a given class type  to be stored in nodes implementing the named element. |
|`appendChild()`|appendChild|Takes 0 args. Method in class javax.imageio.metadata.IIOMetadataNode  Adds the node newChild to the end of the list of  children of this node. |
|`areTablesSet()`|areTablesSet|Takes 0 args. Method in class javax.imageio.plugins.jpeg.JPEGImageReadParam  Returns true if tables are currently set. |
|`areTablesSet()`|areTablesSet|Takes 0 args. Method in class javax.imageio.plugins.jpeg.JPEGImageWriteParam  Returns true if tables are currently set. |
|`accept(${1:AnnotationValueVisitor}, ${2:P})`|accept|Takes 2 args. Method in interface javax.lang.model.element.AnnotationValue  Applies a visitor to this value. |
|`accept(${1:ElementVisitor}, ${2:P})`|accept|Takes 2 args. Method in interface javax.lang.model.element.Element  Applies a visitor to this element. |
|`asType()`|asType|Takes 0 args. Method in interface javax.lang.model.element.Element  Returns the type defined by this element. |
|`asElement()`|asElement|Takes 0 args. Method in interface javax.lang.model.type.DeclaredType  Returns the element corresponding to this type. |
|`accept(${1:TypeVisitor}, ${2:P})`|accept|Takes 2 args. Method in interface javax.lang.model.type.TypeMirror  Applies a visitor to this type. |
|`asElement()`|asElement|Takes 0 args. Method in interface javax.lang.model.type.TypeVariable  Returns the element corresponding to this type variable. |
|`asElement()`|asElement|Takes 0 args. Method in interface javax.lang.model.util.Types  Returns the element corresponding to a type. |
|`asMemberOf(${1:DeclaredType}, ${2:Element})`|asMemberOf|Takes 2 args. Method in interface javax.lang.model.util.Types  Returns the type of an element when that element is viewed as  a member of, or otherwise directly contained by, a given type. |
|`ATTRIBUTE_CHANGE`|ATTRIBUTE_CHANGE|Takes 0 args. Static variable in class javax.management.AttributeChangeNotification  Notification type which indicates that the observed MBean attribute value has changed. |
|`add()`|add|Takes 0 args. Method in class javax.management.AttributeList  Adds the Attribute specified as the last element of the list. |
|`addAll()`|addAll|Takes 0 args. Method in class javax.management.AttributeList  Appends all the elements in the AttributeList specified to  the end of the list, in the order in which they are returned by the  Iterator of the AttributeList specified. |
|`asList()`|asList|Takes 0 args. Method in class javax.management.AttributeList  Return a view of this list as a List. |
|`apply()`|apply|Takes 0 args. Method in class javax.management.AttributeValueExp  Applies the AttributeValueExp on an MBean. |
|`ACTION`|ACTION|Takes 0 args. Static variable in class javax.management.MBeanOperationInfo  Indicates that the operation is write-like: it has an effect but does  not return any information from the MBean. |
|`ACTION_INFO`|ACTION_INFO|Takes 0 args. Static variable in class javax.management.MBeanOperationInfo  Indicates that the operation is both read-like and write-like:  it has an effect, and it also returns information from the MBean. |
|`addNotificationListener(${1:ObjectName}, ${2:ObjectName}, ${3:NotificationFilter}, ${4:Object})`|addNotificationListener|Takes 4 args. Method in interface javax.management.MBeanServer  Adds a listener to a registered MBean. |
|`addNotificationListener(${1:ObjectName}, ${2:ObjectName}, ${3:NotificationFilter}, ${4:Object})`|addNotificationListener|Takes 4 args. Method in interface javax.management.MBeanServerConnection  Adds a listener to a registered MBean. |
|`addNotificationListener(${1:NotificationListener}, ${2:NotificationFilter}, ${3:Object})`|addNotificationListener|Takes 3 args. Method in class javax.management.MBeanServerDelegate  |
|`addNotificationListener(${1:NotificationListener}, ${2:NotificationFilter}, ${3:Object})`|addNotificationListener|Takes 3 args. Method in interface javax.management.NotificationBroadcaster  Adds a listener to this MBean. |
|`addNotificationListener(${1:NotificationListener}, ${2:NotificationFilter}, ${3:Object})`|addNotificationListener|Takes 3 args. Method in class javax.management.NotificationBroadcasterSupport  Adds a listener. |
|`apply()`|apply|Takes 0 args. Method in class javax.management.ObjectName  Test whether this ObjectName, which may be a pattern,  matches another ObjectName. |
|`and(${1:QueryExp}, ${2:QueryExp})`|and|Takes 2 args. Static method in class javax.management.Query  Returns a query expression that is the conjunction of two other query  expressions. |
|`anySubString(${1:AttributeValueExp}, ${2:StringValueExp})`|anySubString|Takes 2 args. Static method in class javax.management.Query  Returns a query expression that represents a matching constraint on  a string argument. |
|`attr(${1:String}, ${2:String})`|attr|Takes 2 args. Static method in class javax.management.Query  Returns a new qualified attribute expression. |
|`apply()`|apply|Takes 0 args. Method in interface javax.management.QueryExp  Applies the QueryExp on an MBean. |
|`addNotificationListener(${1:NotificationListener}, ${2:NotificationFilter}, ${3:Object})`|addNotificationListener|Takes 3 args. Method in class javax.management.StandardEmitterMBean  |
|`apply()`|apply|Takes 0 args. Method in class javax.management.StringValueExp  Applies the ValueExp on a MBean. |
|`apply()`|apply|Takes 0 args. Method in interface javax.management.ValueExp  Applies the ValueExp on a MBean. |
|`addURL()`|addURL|Takes 0 args. Method in class javax.management.loading.MLet  Appends the specified URL to the list of URLs to search for classes and  resources. |
|`addURL()`|addURL|Takes 0 args. Method in interface javax.management.loading.MLetMBean  Appends the specified URL to the list of URLs to search for classes and  resources. |
|`addAttributeChangeNotificationListener(${1:NotificationListener}, ${2:String}, ${3:Object})`|addAttributeChangeNotificationListener|Takes 3 args. Method in interface javax.management.modelmbean.ModelMBeanNotificationBroadcaster  Registers an object which implements the NotificationListener interface as a listener. |
|`addAttributeChangeNotificationListener(${1:NotificationListener}, ${2:String}, ${3:Object})`|addAttributeChangeNotificationListener|Takes 3 args. Method in class javax.management.modelmbean.RequiredModelMBean  |
|`addNotificationListener(${1:NotificationListener}, ${2:NotificationFilter}, ${3:Object})`|addNotificationListener|Takes 3 args. Method in class javax.management.modelmbean.RequiredModelMBean  Registers an object which implements the NotificationListener  interface as a listener. |
|`addObservedObject()`|addObservedObject|Takes 0 args. Method in class javax.management.monitor.Monitor  Adds the specified object in the set of observed MBeans, if this object  is not already present. |
|`alreadyNotifieds`|alreadyNotifieds|Takes 0 args. Variable in class javax.management.monitor.Monitor  Selected monitor errors that have already been notified. |
|`addObservedObject()`|addObservedObject|Takes 0 args. Method in interface javax.management.monitor.MonitorMBean  Adds the specified object in the set of observed MBeans. |
|`ALLOWED_CLASSNAMES_LIST`|ALLOWED_CLASSNAMES_LIST|Takes 0 args. Static variable in class javax.management.openmbean.OpenType  List of the fully qualified names of the Java classes allowed for open  data values. |
|`addRelation()`|addRelation|Takes 0 args. Method in class javax.management.relation.RelationService  Adds an MBean created by the user (and registered by him in the MBean  Server) as a relation in the Relation Service. |
|`addRelationType()`|addRelationType|Takes 0 args. Method in class javax.management.relation.RelationService  Adds given object as a relation type. |
|`addRelation()`|addRelation|Takes 0 args. Method in interface javax.management.relation.RelationServiceMBean  Adds an MBean created by the user (and registered by him in the MBean  Server) as a relation in the Relation Service. |
|`addRelationType()`|addRelationType|Takes 0 args. Method in interface javax.management.relation.RelationServiceMBean  Adds given object as a relation type. |
|`addRoleInfo()`|addRoleInfo|Takes 0 args. Method in class javax.management.relation.RelationTypeSupport  Add a role info. |
|`add()`|add|Takes 0 args. Method in class javax.management.relation.RoleList  Adds the Role specified as the last element of the list. |
|`addAll()`|addAll|Takes 0 args. Method in class javax.management.relation.RoleList  Appends all the elements in the RoleList specified to the end  of the list, in the order in which they are returned by the Iterator of  the RoleList specified. |
|`asList()`|asList|Takes 0 args. Method in class javax.management.relation.RoleList  Return a view of this list as a List. |
|`add()`|add|Takes 0 args. Method in class javax.management.relation.RoleUnresolvedList  Adds the RoleUnresolved specified as the last element of the list. |
|`addAll()`|addAll|Takes 0 args. Method in class javax.management.relation.RoleUnresolvedList  Appends all the elements in the RoleUnresolvedList specified to the end  of the list, in the order in which they are returned by the Iterator of  the RoleUnresolvedList specified. |
|`asList()`|asList|Takes 0 args. Method in class javax.management.relation.RoleUnresolvedList  Return a view of this list as a List. |
|`authenticate()`|authenticate|Takes 0 args. Method in interface javax.management.remote.JMXAuthenticator  Authenticates the MBeanServerConnection client  with the given client credentials. |
|`addConnectionNotificationListener(${1:NotificationListener}, ${2:NotificationFilter}, ${3:Object})`|addConnectionNotificationListener|Takes 3 args. Method in interface javax.management.remote.JMXConnector  Adds a listener to be informed of changes in connection  status. |
|`AUTHENTICATOR`|AUTHENTICATOR|Takes 0 args. Static variable in class javax.management.remote.JMXConnectorServer  Name of the attribute that specifies the authenticator for a  connector server. |
|`addNotificationListener(${1:ObjectName}, ${2:ObjectName}, ${3:MarshalledObject}, ${4:MarshalledObject}, ${5:Subject})`|addNotificationListener|Takes 5 args. Method in interface javax.management.remote.rmi.RMIConnection  Handles the method MBeanServerConnection.addNotificationListener(ObjectName,  ObjectName, NotificationFilter, Object). |
|`addNotificationListeners(${1:ObjectName[]}, ${2:MarshalledObject[]}, ${3:Subject[]})`|addNotificationListeners|Takes 3 args. Method in interface javax.management.remote.rmi.RMIConnection  Handles the method MBeanServerConnection.addNotificationListener(ObjectName,  NotificationListener, NotificationFilter, Object). |
|`addNotificationListener(${1:ObjectName}, ${2:ObjectName}, ${3:MarshalledObject}, ${4:MarshalledObject}, ${5:Subject})`|addNotificationListener|Takes 5 args. Method in class javax.management.remote.rmi.RMIConnectionImpl  |
|`addNotificationListeners(${1:ObjectName[]}, ${2:MarshalledObject[]}, ${3:Subject[]})`|addNotificationListeners|Takes 3 args. Method in class javax.management.remote.rmi.RMIConnectionImpl  |
|`addNotificationListener(${1:ObjectName}, ${2:ObjectName}, ${3:MarshalledObject}, ${4:MarshalledObject}, ${5:Subject})`|addNotificationListener|Takes 5 args. Method in class javax.management.remote.rmi.RMIConnectionImpl_Stub  |
|`addNotificationListeners(${1:ObjectName[]}, ${2:MarshalledObject[]}, ${3:Subject[]})`|addNotificationListeners|Takes 3 args. Method in class javax.management.remote.rmi.RMIConnectionImpl_Stub  |
|`addConnectionNotificationListener(${1:NotificationListener}, ${2:NotificationFilter}, ${3:Object})`|addConnectionNotificationListener|Takes 3 args. Method in class javax.management.remote.rmi.RMIConnector  |
|`addNotification(${1:String}, ${2:String}, ${3:Object}, ${4:Date}, ${5:long}, ${6:long}, ${7:boolean})`|addNotification|Takes 7 args. Method in class javax.management.timer.Timer  Creates a new timer notification with the specified type, message  and userData and inserts it into the list of notifications with a given date,  period and number of occurrences. |
|`addNotification(${1:String}, ${2:String}, ${3:Object}, ${4:Date}, ${5:long}, ${6:long}, ${7:boolean})`|addNotification|Takes 7 args. Method in interface javax.management.timer.TimerMBean  Creates a new timer notification with the specified type, message  and userData and inserts it into the list of notifications with a given date,  period and number of occurrences. |
|`altName`|altName|Takes 0 args. Variable in exception javax.naming.CannotProceedException  Contains the name of the resolved object, relative  to the context altNameCtx. |
|`altNameCtx`|altNameCtx|Takes 0 args. Variable in exception javax.naming.CannotProceedException  Contains the context relative to which  altName is specified. |
|`add()`|add|Takes 0 args. Method in class javax.naming.CompositeName  Adds a single component to the end of this composite name. |
|`addAll()`|addAll|Takes 0 args. Method in class javax.naming.CompositeName  Adds the components of a composite name -- in order -- to the end of  this composite name. |
|`add()`|add|Takes 0 args. Method in class javax.naming.CompoundName  Adds a single component to the end of this compound name. |
|`addAll()`|addAll|Takes 0 args. Method in class javax.naming.CompoundName  Adds the components of a compound name -- in order -- to the end of  this compound name. |
|`APPLET`|APPLET|Takes 0 args. Static variable in interface javax.naming.Context  Constant that holds the name of the environment property for  specifying an applet for the initial context constructor to use  when searching for other properties. |
|`AUTHORITATIVE`|AUTHORITATIVE|Takes 0 args. Static variable in interface javax.naming.Context  Constant that holds the name of the environment property for  specifying the authoritativeness of the service requested. |
|`addToEnvironment(${1:String}, ${2:Object})`|addToEnvironment|Takes 2 args. Method in interface javax.naming.Context  Adds a new environment property to the environment of this  context. |
|`addToEnvironment(${1:String}, ${2:Object})`|addToEnvironment|Takes 2 args. Method in class javax.naming.InitialContext  |
|`add()`|add|Takes 0 args. Method in interface javax.naming.Name  Adds a single component to the end of this name. |
|`addAll()`|addAll|Takes 0 args. Method in interface javax.naming.Name  Adds the components of a name -- in order -- to the end of this name. |
|`appendRemainingComponent()`|appendRemainingComponent|Takes 0 args. Method in exception javax.naming.NamingException  Add name as the last component in remaining name. |
|`appendRemainingName()`|appendRemainingName|Takes 0 args. Method in exception javax.naming.NamingException  Add components from 'name' as the last components in  remaining name. |
|`addrType`|addrType|Takes 0 args. Variable in class javax.naming.RefAddr  Contains the type of this address. |
|`add()`|add|Takes 0 args. Method in class javax.naming.Reference  Adds an address to the end of the list of addresses. |
|`addrs`|addrs|Takes 0 args. Variable in class javax.naming.Reference  Contains the addresses contained in this Reference. |
|`add()`|add|Takes 0 args. Method in interface javax.naming.directory.Attribute  Adds a new value to the attribute. |
|`add()`|add|Takes 0 args. Method in class javax.naming.directory.BasicAttribute  Adds a new value to this attribute. |
|`attrID`|attrID|Takes 0 args. Variable in class javax.naming.directory.BasicAttribute  Holds the attribute's id. |
|`ADD_ATTRIBUTE`|ADD_ATTRIBUTE|Takes 0 args. Static variable in interface javax.naming.directory.DirContext  This constant specifies to add an attribute with the specified values. |
|`addNamingListener(${1:Name}, ${2:int}, ${3:NamingListener})`|addNamingListener|Takes 3 args. Method in interface javax.naming.event.EventContext  Adds a listener for receiving naming events fired  when the object(s) identified by a target and scope changes. |
|`addNamingListener(${1:Name}, ${2:String}, ${3:SearchControls}, ${4:NamingListener})`|addNamingListener|Takes 4 args. Method in interface javax.naming.event.EventDirContext  Adds a listener for receiving naming events fired  when objects identified by the search filter filter at  the object named by target are modified. |
|`add()`|add|Takes 0 args. Method in class javax.naming.ldap.LdapName  Adds a single RDN to the end of this LDAP name. |
|`addAll()`|addAll|Takes 0 args. Method in class javax.naming.ldap.LdapName  Adds the components of a name -- in order -- to the end of this name. |
|`appendRemainingComponent()`|appendRemainingComponent|Takes 0 args. Method in class javax.naming.spi.ResolveResult  Adds a single component to the end of remaining name. |
|`appendRemainingName()`|appendRemainingName|Takes 0 args. Method in class javax.naming.spi.ResolveResult  Adds components to the end of remaining name. |
|`addHandshakeCompletedListener()`|addHandshakeCompletedListener|Takes 0 args. Method in class javax.net.ssl.SSLSocket  Registers an event listener to receive notifications that an  SSL handshake has completed on this connection. |
|`AUTOSENSE`|AUTOSENSE|Takes 0 args. Static variable in class javax.print.DocFlavor.BYTE_ARRAY  Doc flavor with MIME type =  "application/octet-stream",  print data representation class name = "[B" (byte  array). |
|`AUTOSENSE`|AUTOSENSE|Takes 0 args. Static variable in class javax.print.DocFlavor.INPUT_STREAM  Doc flavor with MIME type =  "application/octet-stream",  print data representation class name =  "java.io.InputStream" (byte stream). |
|`AUTOSENSE`|AUTOSENSE|Takes 0 args. Static variable in class javax.print.DocFlavor.URL  Doc flavor with MIME type =  "application/octet-stream",  print data representation class name = "java.net.URL". |
|`addPrintJobAttributeListener(${1:PrintJobAttributeListener}, ${2:PrintJobAttributeSet})`|addPrintJobAttributeListener|Takes 2 args. Method in interface javax.print.DocPrintJob  Registers a listener for changes in the specified attributes. |
|`addPrintJobListener()`|addPrintJobListener|Takes 0 args. Method in interface javax.print.DocPrintJob  Registers a listener for event occurring during this print job. |
|`addPrintServiceAttributeListener()`|addPrintServiceAttributeListener|Takes 0 args. Method in interface javax.print.PrintService  Registers a listener for events on this PrintService. |
|`ABOUT_UIROLE`|ABOUT_UIROLE|Takes 0 args. Static variable in class javax.print.ServiceUIFactory  Denotes a UI which performs an informative "About" role. |
|`ADMIN_UIROLE`|ADMIN_UIROLE|Takes 0 args. Static variable in class javax.print.ServiceUIFactory  Denotes a UI which performs an administrative role. |
|`add()`|add|Takes 0 args. Method in interface javax.print.attribute.AttributeSet  Adds the specified attribute to this attribute set if it is not  already present, first removing any existing value in the same  attribute category as the specified attribute value. |
|`addAll()`|addAll|Takes 0 args. Method in interface javax.print.attribute.AttributeSet  Adds all of the elements in the specified set to this attribute. |
|`add()`|add|Takes 0 args. Method in interface javax.print.attribute.DocAttributeSet  Adds the specified attribute value to this attribute set if it is not  already present, first removing any existing value in the same  attribute category as the specified attribute value (optional  operation). |
|`addAll()`|addAll|Takes 0 args. Method in interface javax.print.attribute.DocAttributeSet  Adds all of the elements in the specified set to this attribute. |
|`add()`|add|Takes 0 args. Method in class javax.print.attribute.HashAttributeSet  Adds the specified attribute to this attribute set if it is not  already present, first removing any existing in the same  attribute category as the specified attribute value. |
|`addAll()`|addAll|Takes 0 args. Method in class javax.print.attribute.HashAttributeSet  Adds all of the elements in the specified set to this attribute. |
|`add()`|add|Takes 0 args. Method in interface javax.print.attribute.PrintJobAttributeSet  Adds the specified attribute value to this attribute set if it is not  already present, first removing any existing value in the same  attribute category as the specified attribute value (optional  operation). |
|`addAll()`|addAll|Takes 0 args. Method in interface javax.print.attribute.PrintJobAttributeSet  Adds all of the elements in the specified set to this attribute. |
|`add()`|add|Takes 0 args. Method in interface javax.print.attribute.PrintRequestAttributeSet  Adds the specified attribute value to this attribute set if it is not  already present, first removing any existing value in the same  attribute category as the specified attribute value (optional  operation). |
|`addAll()`|addAll|Takes 0 args. Method in interface javax.print.attribute.PrintRequestAttributeSet  Adds all of the elements in the specified set to this attribute. |
|`add()`|add|Takes 0 args. Method in interface javax.print.attribute.PrintServiceAttributeSet  Adds the specified attribute value to this attribute set if it is not  already present, first removing any existing value in the same  attribute category as the specified attribute value (optional  operation). |
|`addAll()`|addAll|Takes 0 args. Method in interface javax.print.attribute.PrintServiceAttributeSet  Adds all of the elements in the specified set to this attribute. |
|`ABORTED`|ABORTED|Takes 0 args. Static variable in class javax.print.attribute.standard.JobState  The job has been aborted by the system (usually while the job was in the  PROCESSING or PROCESSING_STOPPED state), the printer has completed  aborting the job, and all job status attributes have reached their final  values for the job. |
|`ABORTED_BY_SYSTEM`|ABORTED_BY_SYSTEM|Takes 0 args. Static variable in class javax.print.attribute.standard.JobStateReason  The job was aborted by the system. |
|`add()`|add|Takes 0 args. Method in class javax.print.attribute.standard.JobStateReasons  Adds the specified element to this job state reasons attribute if it is  not already present. |
|`A0`|A0|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.ISO  Specifies the ISO A0 size, 841 mm by 1189 mm. |
|`A1`|A1|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.ISO  Specifies the ISO A1 size, 594 mm by 841 mm. |
|`A10`|A10|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.ISO  Specifies the ISO A10 size, 26 mm by 37 mm. |
|`A2`|A2|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.ISO  Specifies the ISO A2 size, 420 mm by 594 mm. |
|`A3`|A3|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.ISO  Specifies the ISO A3 size, 297 mm by 420 mm. |
|`A4`|A4|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.ISO  Specifies the ISO A4 size, 210 mm by 297 mm. |
|`A5`|A5|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.ISO  Specifies the ISO A5 size, 148 mm by 210 mm. |
|`A6`|A6|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.ISO  Specifies the ISO A6 size, 105 mm by 148 mm. |
|`A7`|A7|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.ISO  Specifies the ISO A7 size, 74 mm by 105 mm. |
|`A8`|A8|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.ISO  Specifies the ISO A8 size, 52 mm by 74 mm. |
|`A9`|A9|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.ISO  Specifies the ISO A9 size, 37 mm by 52 mm. |
|`ATTEMPTED`|ATTEMPTED|Takes 0 args. Static variable in class javax.print.attribute.standard.PDLOverrideSupported  The printer attempts to make the external job attribute values take  precedence over embedded instructions in the documents' print data,  however there is no guarantee. |
|`ACCEPTING_JOBS`|ACCEPTING_JOBS|Takes 0 args. Static variable in class javax.print.attribute.standard.PrinterIsAcceptingJobs  The printer is currently acccepting jobs. |
|`attributeUpdate()`|attributeUpdate|Takes 0 args. Method in interface javax.print.event.PrintJobAttributeListener  Notifies the listener of a change in some print job attributes. |
|`attributeUpdate()`|attributeUpdate|Takes 0 args. Method in interface javax.print.event.PrintServiceAttributeListener  Called to notify a listener of an event in the print service. |
|`ARGV`|ARGV|Takes 0 args. Static variable in interface javax.script.ScriptEngine  Reserved key for a named value that passes  an array of positional arguments to a script. |
|`allowMultipleSelections()`|allowMultipleSelections|Takes 0 args. Method in class javax.security.auth.callback.ChoiceCallback  Get the boolean determining whether multiple selections from  the choices list are allowed. |
|`abort()`|abort|Takes 0 args. Method in interface javax.security.auth.spi.LoginModule  Method to abort the authentication process (phase 2). |
|`allNotesOff()`|allNotesOff|Takes 0 args. Method in interface javax.sound.midi.MidiChannel  Turns off all notes that are currently sounding on this channel. |
|`allSoundOff()`|allSoundOff|Takes 0 args. Method in interface javax.sound.midi.MidiChannel  Immediately turns off all sounding notes on this channel, ignoring the  state of the Hold Pedal and the internal decay rate of the current  Instrument. |
|`addControllerEventListener(${1:ControllerEventListener}, ${2:int[]})`|addControllerEventListener|Takes 2 args. Method in interface javax.sound.midi.Sequencer  Registers a controller event listener to receive notification  whenever the sequencer processes a control-change event of the  requested type or types. |
|`addMetaEventListener()`|addMetaEventListener|Takes 0 args. Method in interface javax.sound.midi.Sequencer  Registers a meta-event listener to receive  notification whenever a meta-event is encountered in the sequence  and processed by the sequencer. |
|`ACTIVE_SENSING`|ACTIVE_SENSING|Takes 0 args. Static variable in class javax.sound.midi.ShortMessage  Status byte for Active Sensing message (0xFE, or 254). |
|`add()`|add|Takes 0 args. Method in class javax.sound.midi.Track  Adds a new event to the track. |
|`active`|active|Takes 0 args. Variable in class javax.sound.midi.VoiceStatus  Indicates whether the voice is currently processing a MIDI note. |
|`AIFC`|AIFC|Takes 0 args. Static variable in class javax.sound.sampled.AudioFileFormat.Type  Specifies an AIFF-C file. |
|`AIFF`|AIFF|Takes 0 args. Static variable in class javax.sound.sampled.AudioFileFormat.Type  Specifies an AIFF file. |
|`AU`|AU|Takes 0 args. Static variable in class javax.sound.sampled.AudioFileFormat.Type  Specifies an AU file. |
|`ALAW`|ALAW|Takes 0 args. Static variable in class javax.sound.sampled.AudioFormat.Encoding  Specifies a-law encoded data. |
|`available()`|available|Takes 0 args. Method in class javax.sound.sampled.AudioInputStream  Returns the maximum number of bytes that can be read (or skipped over) from this  audio input stream without blocking. |
|`APPLY_REVERB`|APPLY_REVERB|Takes 0 args. Static variable in class javax.sound.sampled.BooleanControl.Type  Represents a control for whether reverberation is applied  to a line. |
|`available()`|available|Takes 0 args. Method in interface javax.sound.sampled.DataLine  Obtains the number of bytes of data currently available to the  application for processing in the data line's internal buffer. |
|`AUX_RETURN`|AUX_RETURN|Takes 0 args. Static variable in class javax.sound.sampled.FloatControl.Type  Represents a control for the auxiliary return gain on a line. |
|`AUX_SEND`|AUX_SEND|Takes 0 args. Static variable in class javax.sound.sampled.FloatControl.Type  Represents a control for the auxiliary send gain on a line. |
|`addLineListener()`|addLineListener|Takes 0 args. Method in interface javax.sound.sampled.Line  Adds a listener to this line. |
|`addConnectionEventListener()`|addConnectionEventListener|Takes 0 args. Method in interface javax.sql.PooledConnection  Registers the given event listener so that it will be notified  when an event occurs on this PooledConnection object. |
|`addStatementEventListener()`|addStatementEventListener|Takes 0 args. Method in interface javax.sql.PooledConnection  Registers a StatementEventListener with this PooledConnection object. |
|`addRowSetListener()`|addRowSetListener|Takes 0 args. Method in interface javax.sql.RowSet  Registers the given listener so that it will be notified of events  that occur on this RowSet object. |
|`ASCII_STREAM_PARAM`|ASCII_STREAM_PARAM|Takes 0 args. Static variable in class javax.sql.rowset.BaseRowSet  A constant indicating to a RowSetReaderImpl object  that a given parameter is an ASCII stream. |
|`addRowSetListener()`|addRowSetListener|Takes 0 args. Method in class javax.sql.rowset.BaseRowSet  The listener will be notified whenever an event occurs on this RowSet  object. |
|`asciiStream`|asciiStream|Takes 0 args. Variable in class javax.sql.rowset.BaseRowSet  The InputStream object that will be  returned by the method getAsciiStream,  which is specified in the ResultSet interface. |
|`acceptChanges()`|acceptChanges|Takes 0 args. Method in interface javax.sql.rowset.CachedRowSet  Propagates all row update, insert and delete changes to the  data source backing this CachedRowSet object  using the specified Connection object to establish a  connection to the data source. |
|`addRowSet()`|addRowSet|Takes 0 args. Method in interface javax.sql.rowset.JoinRowSet  Adds the given RowSet object to this JoinRowSet  object. |
|`addPropertyChangeListener()`|addPropertyChangeListener|Takes 0 args. Method in class javax.swing.AbstractAction  Adds a PropertyChangeListener to the listener list. |
|`actionListener`|actionListener|Takes 0 args. Variable in class javax.swing.AbstractButton  The button model's ActionListener. |
|`actionPropertyChanged(${1:Action}, ${2:String})`|actionPropertyChanged|Takes 2 args. Method in class javax.swing.AbstractButton  Updates the button's state in response to property changes in the  associated action. |
|`addActionListener()`|addActionListener|Takes 0 args. Method in class javax.swing.AbstractButton  Adds an ActionListener to the button. |
|`addChangeListener()`|addChangeListener|Takes 0 args. Method in class javax.swing.AbstractButton  Adds a ChangeListener to the button. |
|`addImpl(${1:Component}, ${2:Object}, ${3:int})`|addImpl|Takes 3 args. Method in class javax.swing.AbstractButton  Adds the specified component to this container at the specified  index, refer to  Container.addImpl(Component, Object, int)  for a complete description of this method. |
|`addItemListener()`|addItemListener|Takes 0 args. Method in class javax.swing.AbstractButton  Adds an ItemListener to the checkbox. |
|`addCellEditorListener()`|addCellEditorListener|Takes 0 args. Method in class javax.swing.AbstractCellEditor  Adds a CellEditorListener to the listener list. |
|`addListDataListener()`|addListDataListener|Takes 0 args. Method in class javax.swing.AbstractListModel  Adds a listener to the list that's notified each time a change  to the data model occurs. |
|`addChangeListener()`|addChangeListener|Takes 0 args. Method in class javax.swing.AbstractSpinnerModel  Adds a ChangeListener to the model's listener list. |
|`ACCELERATOR_KEY`|ACCELERATOR_KEY|Takes 0 args. Static variable in interface javax.swing.Action  The key used for storing a KeyStroke to be used as the  accelerator for the action. |
|`ACTION_COMMAND_KEY`|ACTION_COMMAND_KEY|Takes 0 args. Static variable in interface javax.swing.Action  The key used to determine the command String for the  ActionEvent that will be created when an  Action is going to be notified as the result of  residing in a Keymap associated with a  JComponent. |
|`addPropertyChangeListener()`|addPropertyChangeListener|Takes 0 args. Method in interface javax.swing.Action  Adds a PropertyChange listener. |
|`allKeys()`|allKeys|Takes 0 args. Method in class javax.swing.ActionMap  Returns an array of the keys defined in this ActionMap and  its parent. |
|`addChangeListener()`|addChangeListener|Takes 0 args. Method in interface javax.swing.BoundedRangeModel  Adds a ChangeListener to the model's listener list. |
|`addLayoutComponent(${1:String}, ${2:Component})`|addLayoutComponent|Takes 2 args. Method in class javax.swing.BoxLayout  Not used by this class. |
|`add()`|add|Takes 0 args. Method in class javax.swing.ButtonGroup  Adds the button to the group. |
|`addActionListener()`|addActionListener|Takes 0 args. Method in interface javax.swing.ButtonModel  Adds an ActionListener to the model. |
|`addChangeListener()`|addChangeListener|Takes 0 args. Method in interface javax.swing.ButtonModel  Adds a ChangeListener to the model. |
|`addItemListener()`|addItemListener|Takes 0 args. Method in interface javax.swing.ButtonModel  Adds an ItemListener to the model. |
|`addCellEditorListener()`|addCellEditorListener|Takes 0 args. Method in interface javax.swing.CellEditor  Adds a listener to the list that's notified when the editor  stops, or cancels editing. |
|`accessibleContext`|accessibleContext|Takes 0 args. Variable in class javax.swing.CellRendererPane  |
|`addImpl(${1:Component}, ${2:Object}, ${3:int})`|addImpl|Takes 3 args. Method in class javax.swing.CellRendererPane  If the specified component is already a child of this then we don't  bother doing anything|
|`addActionListener()`|addActionListener|Takes 0 args. Method in interface javax.swing.ComboBoxEditor  Add an ActionListener. |
|`addChangeListener()`|addChangeListener|Takes 0 args. Method in class javax.swing.DefaultBoundedRangeModel  Adds a ChangeListener. |
|`ARMED`|ARMED|Takes 0 args. Static variable in class javax.swing.DefaultButtonModel  Identifies the "armed" bit in the bitmask, which  indicates partial commitment towards choosing/triggering  the button. |
|`actionCommand`|actionCommand|Takes 0 args. Variable in class javax.swing.DefaultButtonModel  The action command string fired by the button. |
|`addActionListener()`|addActionListener|Takes 0 args. Method in class javax.swing.DefaultButtonModel  Adds an ActionListener to the model. |
|`addChangeListener()`|addChangeListener|Takes 0 args. Method in class javax.swing.DefaultButtonModel  Adds a ChangeListener to the model. |
|`addItemListener()`|addItemListener|Takes 0 args. Method in class javax.swing.DefaultButtonModel  Adds an ItemListener to the model. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.DefaultCellEditor.EditorDelegate  When an action is performed, editing is ended. |
|`addElement()`|addElement|Takes 0 args. Method in class javax.swing.DefaultComboBoxModel  |
|`activateFrame()`|activateFrame|Takes 0 args. Method in class javax.swing.DefaultDesktopManager  This will activate f moving it to the front. |
|`add(${1:int}, ${2:E})`|add|Takes 2 args. Method in class javax.swing.DefaultListModel  Inserts the specified element at the specified position in this list. |
|`addElement()`|addElement|Takes 0 args. Method in class javax.swing.DefaultListModel  Adds the specified component to the end of this list. |
|`addListSelectionListener()`|addListSelectionListener|Takes 0 args. Method in class javax.swing.DefaultListSelectionModel  Add a listener to the list that's notified each time a change  to the selection occurs. |
|`addSelectionInterval(${1:int}, ${2:int})`|addSelectionInterval|Takes 2 args. Method in class javax.swing.DefaultListSelectionModel  Changes the selection to be the set union of the current selection  and the indices between index0 and index1 inclusive. |
|`allRowsChanged()`|allRowsChanged|Takes 0 args. Method in class javax.swing.DefaultRowSorter  Invoked when the contents of the underlying model have  completely changed. |
|`addChangeListener()`|addChangeListener|Takes 0 args. Method in class javax.swing.DefaultSingleSelectionModel  Adds a ChangeListener to the button. |
|`activateFrame()`|activateFrame|Takes 0 args. Method in interface javax.swing.DesktopManager  Generally, indicate that this frame has focus. |
|`addComponent(${1:Component}, ${2:int}, ${3:int}, ${4:int})`|addComponent|Takes 4 args. Method in class javax.swing.GroupLayout.Group  Adds a Component to this Group  with the specified size. |
|`addGap(${1:int}, ${2:int}, ${3:int})`|addGap|Takes 3 args. Method in class javax.swing.GroupLayout.Group  Adds a gap to this Group with the specified size. |
|`addGroup()`|addGroup|Takes 0 args. Method in class javax.swing.GroupLayout.Group  Adds a Group to this Group. |
|`addComponent(${1:Component}, ${2:GroupLayout.Alignment}, ${3:int}, ${4:int}, ${5:int})`|addComponent|Takes 5 args. Method in class javax.swing.GroupLayout.ParallelGroup  Adds a Component to this ParallelGroup with the  specified alignment and size. |
|`addGap(${1:int}, ${2:int}, ${3:int})`|addGap|Takes 3 args. Method in class javax.swing.GroupLayout.ParallelGroup  Adds a gap to this Group with the specified size. |
|`addGroup()`|addGroup|Takes 0 args. Method in class javax.swing.GroupLayout.ParallelGroup  Adds a Group to this Group. |
|`addComponent(${1:Component}, ${2:int}, ${3:int}, ${4:int})`|addComponent|Takes 4 args. Method in class javax.swing.GroupLayout.SequentialGroup  Adds a Component to this Group  with the specified size. |
|`addContainerGap(${1:int}, ${2:int})`|addContainerGap|Takes 2 args. Method in class javax.swing.GroupLayout.SequentialGroup  Adds an element representing the preferred gap between one  edge of the container and the next or previous Component with the specified size. |
|`addGap(${1:int}, ${2:int}, ${3:int})`|addGap|Takes 3 args. Method in class javax.swing.GroupLayout.SequentialGroup  Adds a gap to this Group with the specified size. |
|`addGroup()`|addGroup|Takes 0 args. Method in class javax.swing.GroupLayout.SequentialGroup  Adds a Group to this Group. |
|`addPreferredGap(${1:LayoutStyle.ComponentPlacement}, ${2:int}, ${3:int})`|addPreferredGap|Takes 3 args. Method in class javax.swing.GroupLayout.SequentialGroup  Adds an element representing the preferred gap between the  nearest components. |
|`addLayoutComponent(${1:String}, ${2:Component})`|addLayoutComponent|Takes 2 args. Method in class javax.swing.GroupLayout  Notification that a Component has been added to  the parent container. |
|`allKeys()`|allKeys|Takes 0 args. Method in class javax.swing.InputMap  Returns an array of the KeyStrokes defined in this  InputMap and its parent. |
|`accessibleContext`|accessibleContext|Takes 0 args. Variable in class javax.swing.JApplet  |
|`addImpl(${1:Component}, ${2:Object}, ${3:int})`|addImpl|Takes 3 args. Method in class javax.swing.JApplet  Adds the specified child Component. |
|`accessibleContext`|accessibleContext|Takes 0 args. Variable in class javax.swing.JColorChooser  |
|`addChooserPanel()`|addChooserPanel|Takes 0 args. Method in class javax.swing.JColorChooser  Adds a color chooser panel to the color chooser. |
|`addAccessibleSelection()`|addAccessibleSelection|Takes 0 args. Method in class javax.swing.JComboBox.AccessibleJComboBox  Adds the specified Accessible child of the object to the object's  selection. |
|`actionCommand`|actionCommand|Takes 0 args. Variable in class javax.swing.JComboBox  This protected field is implementation specific. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.JComboBox  This method is public as an implementation side effect. |
|`actionPropertyChanged(${1:Action}, ${2:String})`|actionPropertyChanged|Takes 2 args. Method in class javax.swing.JComboBox  Updates the combobox's state in response to property changes in  associated action. |
|`addActionListener()`|addActionListener|Takes 0 args. Method in class javax.swing.JComboBox  Adds an ActionListener. |
|`addItem()`|addItem|Takes 0 args. Method in class javax.swing.JComboBox  Adds an item to the item list. |
|`addItemListener()`|addItemListener|Takes 0 args. Method in class javax.swing.JComboBox  Adds an ItemListener. |
|`addPopupMenuListener()`|addPopupMenuListener|Takes 0 args. Method in class javax.swing.JComboBox  Adds a PopupMenu listener which will listen to notification  messages from the popup portion of the combo box. |
|`accessibleFocusHandler`|accessibleFocusHandler|Takes 0 args. Variable in class javax.swing.JComponent.AccessibleJComponent  |
|`addPropertyChangeListener()`|addPropertyChangeListener|Takes 0 args. Method in class javax.swing.JComponent.AccessibleJComponent  Adds a PropertyChangeListener to the listener list. |
|`accessibleContext`|accessibleContext|Takes 0 args. Variable in class javax.swing.JComponent  The AccessibleContext associated with this  JComponent. |
|`addAncestorListener()`|addAncestorListener|Takes 0 args. Method in class javax.swing.JComponent  Registers listener so that it will receive  AncestorEvents when it or any of its ancestors  move or are made visible or invisible. |
|`addNotify()`|addNotify|Takes 0 args. Method in class javax.swing.JComponent  Notifies this component that it now has a parent component. |
|`addVetoableChangeListener()`|addVetoableChangeListener|Takes 0 args. Method in class javax.swing.JComponent  Adds a VetoableChangeListener to the listener list. |
|`addImpl(${1:Component}, ${2:Object}, ${3:int})`|addImpl|Takes 3 args. Method in class javax.swing.JDesktopPane  Adds the specified component to this container at the specified  index. |
|`accessibleContext`|accessibleContext|Takes 0 args. Variable in class javax.swing.JDialog  |
|`addImpl(${1:Component}, ${2:Object}, ${3:int})`|addImpl|Takes 3 args. Method in class javax.swing.JDialog  Adds the specified child Component. |
|`addHyperlinkListener()`|addHyperlinkListener|Takes 0 args. Method in class javax.swing.JEditorPane  Adds a hyperlink listener for notification of any changes, for example  when a link is selected and entered. |
|`ACCEPT_ALL_FILE_FILTER_USED_CHANGED_PROPERTY`|ACCEPT_ALL_FILE_FILTER_USED_CHANGED_PROPERTY|Takes 0 args. Static variable in class javax.swing.JFileChooser  Identifies whether a the AcceptAllFileFilter is used or not. |
|`ACCESSORY_CHANGED_PROPERTY`|ACCESSORY_CHANGED_PROPERTY|Takes 0 args. Static variable in class javax.swing.JFileChooser  Says that a different accessory component is in use  (for example, to preview files). |
|`APPROVE_BUTTON_MNEMONIC_CHANGED_PROPERTY`|APPROVE_BUTTON_MNEMONIC_CHANGED_PROPERTY|Takes 0 args. Static variable in class javax.swing.JFileChooser  Identifies change in the mnemonic for the approve (yes, ok) button. |
|`APPROVE_BUTTON_TEXT_CHANGED_PROPERTY`|APPROVE_BUTTON_TEXT_CHANGED_PROPERTY|Takes 0 args. Static variable in class javax.swing.JFileChooser  Identifies change in the text on the approve (yes, ok) button. |
|`APPROVE_BUTTON_TOOL_TIP_TEXT_CHANGED_PROPERTY`|APPROVE_BUTTON_TOOL_TIP_TEXT_CHANGED_PROPERTY|Takes 0 args. Static variable in class javax.swing.JFileChooser  Identifies change in the tooltip text for the approve (yes, ok)  button. |
|`APPROVE_OPTION`|APPROVE_OPTION|Takes 0 args. Static variable in class javax.swing.JFileChooser  Return value if approve (yes, ok) is chosen. |
|`APPROVE_SELECTION`|APPROVE_SELECTION|Takes 0 args. Static variable in class javax.swing.JFileChooser  Instruction to approve the current selection  (same as pressing yes or ok). |
|`accept()`|accept|Takes 0 args. Method in class javax.swing.JFileChooser  Returns true if the file should be displayed. |
|`accessibleContext`|accessibleContext|Takes 0 args. Variable in class javax.swing.JFileChooser  |
|`addActionListener()`|addActionListener|Takes 0 args. Method in class javax.swing.JFileChooser  Adds an ActionListener to the file chooser. |
|`addChoosableFileFilter()`|addChoosableFileFilter|Takes 0 args. Method in class javax.swing.JFileChooser  Adds a filter to the list of user choosable file filters. |
|`approveSelection()`|approveSelection|Takes 0 args. Method in class javax.swing.JFileChooser  Called by the UI when the user hits the Approve button  (labeled "Open" or "Save", by default). |
|`accessibleContext`|accessibleContext|Takes 0 args. Variable in class javax.swing.JFrame  The accessible context property. |
|`addImpl(${1:Component}, ${2:Object}, ${3:int})`|addImpl|Takes 3 args. Method in class javax.swing.JFrame  Adds the specified child Component. |
|`addImpl(${1:Component}, ${2:Object}, ${3:int})`|addImpl|Takes 3 args. Method in class javax.swing.JInternalFrame  Adds the specified child Component. |
|`addInternalFrameListener()`|addInternalFrameListener|Takes 0 args. Method in class javax.swing.JInternalFrame  Adds the specified listener to receive internal  frame events from this internal frame. |
|`addImpl(${1:Component}, ${2:Object}, ${3:int})`|addImpl|Takes 3 args. Method in class javax.swing.JLayer  This method is not supported by JLayer  and always throws UnsupportedOperationException |
|`addNotify()`|addNotify|Takes 0 args. Method in class javax.swing.JLayer  Notifies this component that it now has a parent component. |
|`addImpl(${1:Component}, ${2:Object}, ${3:int})`|addImpl|Takes 3 args. Method in class javax.swing.JLayeredPane  |
|`addFocusListener()`|addFocusListener|Takes 0 args. Method in class javax.swing.JList.AccessibleJList.AccessibleJListChild  |
|`addPropertyChangeListener()`|addPropertyChangeListener|Takes 0 args. Method in class javax.swing.JList.AccessibleJList.AccessibleJListChild  |
|`addAccessibleSelection()`|addAccessibleSelection|Takes 0 args. Method in class javax.swing.JList.AccessibleJList  Adds the specified selected item in the object to the object's  selection. |
|`addListSelectionListener()`|addListSelectionListener|Takes 0 args. Method in class javax.swing.JList  Adds a listener to the list, to be notified each time a change to the  selection occurs; the preferred way of listening for selection state  changes. |
|`addSelectionInterval(${1:int}, ${2:int})`|addSelectionInterval|Takes 2 args. Method in class javax.swing.JList  Sets the selection to be the union of the specified interval with current  selection. |
|`addAccessibleSelection()`|addAccessibleSelection|Takes 0 args. Method in class javax.swing.JMenu.AccessibleJMenu  Selects the ith menu in the menu. |
|`add()`|add|Takes 0 args. Method in class javax.swing.JMenu  Appends a menu item to the end of this menu. |
|`addMenuListener()`|addMenuListener|Takes 0 args. Method in class javax.swing.JMenu  Adds a listener for menu events. |
|`addSeparator()`|addSeparator|Takes 0 args. Method in class javax.swing.JMenu  Appends a new separator to the end of the menu. |
|`applyComponentOrientation()`|applyComponentOrientation|Takes 0 args. Method in class javax.swing.JMenu  Sets the ComponentOrientation property of this menu  and all components contained within it. |
|`addAccessibleSelection()`|addAccessibleSelection|Takes 0 args. Method in class javax.swing.JMenuBar.AccessibleJMenuBar  Selects the nth menu in the menu bar, forcing it to  pop up. |
|`add()`|add|Takes 0 args. Method in class javax.swing.JMenuBar  Appends the specified menu to the end of the menu bar. |
|`addNotify()`|addNotify|Takes 0 args. Method in class javax.swing.JMenuBar  Overrides JComponent.addNotify to register this  menu bar with the current keyboard manager. |
|`actionPropertyChanged(${1:Action}, ${2:String})`|actionPropertyChanged|Takes 2 args. Method in class javax.swing.JMenuItem  Updates the button's state in response to property changes in the  associated action. |
|`addMenuDragMouseListener()`|addMenuDragMouseListener|Takes 0 args. Method in class javax.swing.JMenuItem  Adds a MenuDragMouseListener to the menu item. |
|`addMenuKeyListener()`|addMenuKeyListener|Takes 0 args. Method in class javax.swing.JMenuItem  Adds a MenuKeyListener to the menu item. |
|`add()`|add|Takes 0 args. Method in class javax.swing.JPopupMenu  Appends the specified menu item to the end of this menu. |
|`addMenuKeyListener()`|addMenuKeyListener|Takes 0 args. Method in class javax.swing.JPopupMenu  Adds a MenuKeyListener to the popup menu. |
|`addPopupMenuListener()`|addPopupMenuListener|Takes 0 args. Method in class javax.swing.JPopupMenu  Adds a PopupMenu listener. |
|`addSeparator()`|addSeparator|Takes 0 args. Method in class javax.swing.JPopupMenu  Appends a new separator at the end of the menu. |
|`addChangeListener()`|addChangeListener|Takes 0 args. Method in class javax.swing.JProgressBar  Adds the specified ChangeListener to the progress bar. |
|`addLayoutComponent(${1:String}, ${2:Component})`|addLayoutComponent|Takes 2 args. Method in class javax.swing.JRootPane.RootLayout  |
|`addImpl(${1:Component}, ${2:Object}, ${3:int})`|addImpl|Takes 3 args. Method in class javax.swing.JRootPane  Overridden to enforce the position of the glass component as  the zero child. |
|`addNotify()`|addNotify|Takes 0 args. Method in class javax.swing.JRootPane  Notifies this component that it now has a parent component. |
|`addAdjustmentListener()`|addAdjustmentListener|Takes 0 args. Method in class javax.swing.JScrollBar  Adds an AdjustmentListener. |
|`addChangeListener()`|addChangeListener|Takes 0 args. Method in class javax.swing.JSlider  Adds a ChangeListener to the slider. |
|`addLayoutComponent(${1:String}, ${2:Component})`|addLayoutComponent|Takes 2 args. Method in class javax.swing.JSpinner.DefaultEditor  This LayoutManager method does nothing. |
|`addChangeListener()`|addChangeListener|Takes 0 args. Method in class javax.swing.JSpinner  Adds a listener to the list that is notified each time a change  to the model occurs. |
|`addImpl(${1:Component}, ${2:Object}, ${3:int})`|addImpl|Takes 3 args. Method in class javax.swing.JSplitPane  Adds the specified component to this split pane. |
|`addAccessibleSelection()`|addAccessibleSelection|Takes 0 args. Method in class javax.swing.JTabbedPane.AccessibleJTabbedPane  |
|`add(${1:String}, ${2:Component})`|add|Takes 2 args. Method in class javax.swing.JTabbedPane  Adds a component with the specified tab title. |
|`addChangeListener()`|addChangeListener|Takes 0 args. Method in class javax.swing.JTabbedPane  Adds a ChangeListener to this tabbedpane. |
|`addTab(${1:String}, ${2:Icon}, ${3:Component}, ${4:String})`|addTab|Takes 4 args. Method in class javax.swing.JTabbedPane  Adds a component and tip  represented by a title and/or icon,  either of which can be null. |
|`addFocusListener()`|addFocusListener|Takes 0 args. Method in class javax.swing.JTable.AccessibleJTable.AccessibleJTableCell  |
|`addPropertyChangeListener()`|addPropertyChangeListener|Takes 0 args. Method in class javax.swing.JTable.AccessibleJTable.AccessibleJTableCell  Adds a PropertyChangeListener to the listener list. |
|`addAccessibleSelection()`|addAccessibleSelection|Takes 0 args. Method in class javax.swing.JTable.AccessibleJTable  Adds the specified Accessible child of the  object to the object's selection. |
|`AUTO_RESIZE_ALL_COLUMNS`|AUTO_RESIZE_ALL_COLUMNS|Takes 0 args. Static variable in class javax.swing.JTable  During all resize operations, proportionately resize all columns. |
|`AUTO_RESIZE_LAST_COLUMN`|AUTO_RESIZE_LAST_COLUMN|Takes 0 args. Static variable in class javax.swing.JTable  During all resize operations, apply adjustments to the last column only. |
|`AUTO_RESIZE_NEXT_COLUMN`|AUTO_RESIZE_NEXT_COLUMN|Takes 0 args. Static variable in class javax.swing.JTable  When a column is adjusted in the UI, adjust the next column the opposite way. |
|`AUTO_RESIZE_OFF`|AUTO_RESIZE_OFF|Takes 0 args. Static variable in class javax.swing.JTable  Do not adjust column widths automatically; use a horizontal scrollbar instead. |
|`AUTO_RESIZE_SUBSEQUENT_COLUMNS`|AUTO_RESIZE_SUBSEQUENT_COLUMNS|Takes 0 args. Static variable in class javax.swing.JTable  During UI adjustment, change subsequent columns to preserve the total width;  this is the default behavior. |
|`addColumn()`|addColumn|Takes 0 args. Method in class javax.swing.JTable  Appends aColumn to the end of the array of columns held by   this JTable's column model. |
|`addColumnSelectionInterval(${1:int}, ${2:int})`|addColumnSelectionInterval|Takes 2 args. Method in class javax.swing.JTable  Adds the columns from index0 to index1,  inclusive, to the current selection. |
|`addNotify()`|addNotify|Takes 0 args. Method in class javax.swing.JTable  Calls the configureEnclosingScrollPane method. |
|`addRowSelectionInterval(${1:int}, ${2:int})`|addRowSelectionInterval|Takes 2 args. Method in class javax.swing.JTable  Adds the rows from index0 to index1, inclusive, to  the current selection. |
|`autoCreateColumnsFromModel`|autoCreateColumnsFromModel|Takes 0 args. Variable in class javax.swing.JTable  The table will query the TableModel to build the default   set of columns if this is true. |
|`autoResizeMode`|autoResizeMode|Takes 0 args. Variable in class javax.swing.JTable  Determines if the table automatically resizes the   width of the table's columns to take up the entire width of the   table, and how it does the resizing. |
|`append()`|append|Takes 0 args. Method in class javax.swing.JTextArea  Appends the given text to the end of the document. |
|`actionPropertyChanged(${1:Action}, ${2:String})`|actionPropertyChanged|Takes 2 args. Method in class javax.swing.JTextField  Updates the textfield's state in response to property changes in  associated action. |
|`addActionListener()`|addActionListener|Takes 0 args. Method in class javax.swing.JTextField  Adds the specified action listener to receive  action events from this textfield. |
|`addStyle(${1:String}, ${2:Style})`|addStyle|Takes 2 args. Method in class javax.swing.JTextPane  Adds a new style into the logical style hierarchy. |
|`add()`|add|Takes 0 args. Method in class javax.swing.JToolBar  Adds a new JButton which dispatches the action. |
|`addImpl(${1:Component}, ${2:Object}, ${3:int})`|addImpl|Takes 3 args. Method in class javax.swing.JToolBar  If a JButton is being added, it is initially  set to be disabled. |
|`addSeparator()`|addSeparator|Takes 0 args. Method in class javax.swing.JToolBar  Appends a separator of a specified size to the end  of the tool bar. |
|`addAccessibleSelection()`|addAccessibleSelection|Takes 0 args. Method in class javax.swing.JTree.AccessibleJTree.AccessibleJTreeNode  Adds the specified selected item in the object to the object's  selection. |
|`addFocusListener()`|addFocusListener|Takes 0 args. Method in class javax.swing.JTree.AccessibleJTree.AccessibleJTreeNode  |
|`addPropertyChangeListener()`|addPropertyChangeListener|Takes 0 args. Method in class javax.swing.JTree.AccessibleJTree.AccessibleJTreeNode  Add a PropertyChangeListener to the listener list. |
|`addAccessibleSelection()`|addAccessibleSelection|Takes 0 args. Method in class javax.swing.JTree.AccessibleJTree  Adds the specified selected item in the object to the object's  selection. |
|`addPropertyChangeListener()`|addPropertyChangeListener|Takes 0 args. Method in class javax.swing.JTree.EmptySelectionModel  This is overriden to do nothing; EmptySelectionModel  does not allow a selection. |
|`addSelectionPaths()`|addSelectionPaths|Takes 0 args. Method in class javax.swing.JTree.EmptySelectionModel  This is overriden to do nothing; EmptySelectionModel  does not allow a selection. |
|`addTreeSelectionListener()`|addTreeSelectionListener|Takes 0 args. Method in class javax.swing.JTree.EmptySelectionModel  This is overriden to do nothing; EmptySelectionModel  does not allow a selection. |
|`ANCHOR_SELECTION_PATH_PROPERTY`|ANCHOR_SELECTION_PATH_PROPERTY|Takes 0 args. Static variable in class javax.swing.JTree  Bound property name for anchor selection path. |
|`addSelectionInterval(${1:int}, ${2:int})`|addSelectionInterval|Takes 2 args. Method in class javax.swing.JTree  Adds the specified rows (inclusive) to the selection. |
|`addSelectionPath()`|addSelectionPath|Takes 0 args. Method in class javax.swing.JTree  Adds the node identified by the specified TreePath  to the current selection. |
|`addSelectionPaths()`|addSelectionPaths|Takes 0 args. Method in class javax.swing.JTree  Adds each path in the array of paths to the current selection. |
|`addSelectionRow()`|addSelectionRow|Takes 0 args. Method in class javax.swing.JTree  Adds the path at the specified row to the current selection. |
|`addSelectionRows()`|addSelectionRows|Takes 0 args. Method in class javax.swing.JTree  Adds the paths at each of the specified rows to the current selection. |
|`addTreeExpansionListener()`|addTreeExpansionListener|Takes 0 args. Method in class javax.swing.JTree  Adds a listener for TreeExpansion events. |
|`addTreeSelectionListener()`|addTreeSelectionListener|Takes 0 args. Method in class javax.swing.JTree  Adds a listener for TreeSelection events. |
|`addTreeWillExpandListener()`|addTreeWillExpandListener|Takes 0 args. Method in class javax.swing.JTree  Adds a listener for TreeWillExpand events. |
|`addChangeListener()`|addChangeListener|Takes 0 args. Method in class javax.swing.JViewport  Adds a ChangeListener to the list that is  notified each time the view's  size, position, or the viewport's extent size has changed. |
|`addImpl(${1:Component}, ${2:Object}, ${3:int})`|addImpl|Takes 3 args. Method in class javax.swing.JViewport  Sets the JViewport's one lightweight child,  which can be null. |
|`accessibleContext`|accessibleContext|Takes 0 args. Variable in class javax.swing.JWindow  The accessible context property. |
|`addImpl(${1:Component}, ${2:Object}, ${3:int})`|addImpl|Takes 3 args. Method in class javax.swing.JWindow  Adds the specified child Component. |
|`accept()`|accept|Takes 0 args. Method in class javax.swing.LayoutFocusTraversalPolicy  Determines whether the specified Component  is an acceptable choice as the new focus owner. |
|`addListDataListener()`|addListDataListener|Takes 0 args. Method in interface javax.swing.ListModel  Adds a listener to the list that's notified each time a change  to the data model occurs. |
|`addListSelectionListener()`|addListSelectionListener|Takes 0 args. Method in interface javax.swing.ListSelectionModel  Add a listener to the list that's notified each time a change  to the selection occurs. |
|`addSelectionInterval(${1:int}, ${2:int})`|addSelectionInterval|Takes 2 args. Method in interface javax.swing.ListSelectionModel  Changes the selection to be the set union of the current selection  and the indices between index0 and index1 inclusive. |
|`addChangeListener()`|addChangeListener|Takes 0 args. Method in class javax.swing.MenuSelectionManager  Adds a ChangeListener to the button. |
|`addElement()`|addElement|Takes 0 args. Method in interface javax.swing.MutableComboBoxModel  Adds an item at the end of the model. |
|`addLayoutComponent(${1:String}, ${2:Component})`|addLayoutComponent|Takes 2 args. Method in class javax.swing.OverlayLayout  Adds the specified component to the layout. |
|`accessibleContext`|accessibleContext|Takes 0 args. Variable in class javax.swing.ProgressMonitor  The AccessibleContext for the ProgressMonitor |
|`addDirtyRegion(${1:JComponent}, ${2:int}, ${3:int}, ${4:int}, ${5:int})`|addDirtyRegion|Takes 5 args. Method in class javax.swing.RepaintManager  Add a component in the list of components that should be refreshed. |
|`addInvalidComponent()`|addInvalidComponent|Takes 0 args. Method in class javax.swing.RepaintManager  Mark the component as in need of layout and queue a runnable  for the event dispatching thread that will validate the components  first isValidateRoot() ancestor. |
|`andFilter()`|andFilter|Takes 0 args. Static method in class javax.swing.RowFilter  Returns a RowFilter that includes entries if all  of the supplied filters include the entry. |
|`addRowSorterListener()`|addRowSorterListener|Takes 0 args. Method in class javax.swing.RowSorter  Adds a RowSorterListener to receive notification  about this RowSorter. |
|`allRowsChanged()`|allRowsChanged|Takes 0 args. Method in class javax.swing.RowSorter  Invoked when the contents of the underlying model have  completely changed. |
|`addLayoutComponent(${1:String}, ${2:Component})`|addLayoutComponent|Takes 2 args. Method in class javax.swing.ScrollPaneLayout  Adds the specified component to the layout. |
|`addSingletonComponent(${1:Component}, ${2:Component})`|addSingletonComponent|Takes 2 args. Method in class javax.swing.ScrollPaneLayout  Removes an existing component. |
|`addChangeListener()`|addChangeListener|Takes 0 args. Method in interface javax.swing.SingleSelectionModel  Adds listener as a listener to changes in the model. |
|`adjustSizes(${1:int}, ${2:SizeRequirements[]})`|adjustSizes|Takes 2 args. Static method in class javax.swing.SizeRequirements  Adjust a specified array of sizes by a given amount. |
|`alignment`|alignment|Takes 0 args. Variable in class javax.swing.SizeRequirements  The alignment, specified as a value between 0.0 and 1.0,  inclusive. |
|`accept()`|accept|Takes 0 args. Method in class javax.swing.SortingFocusTraversalPolicy  Determines whether a Component is an acceptable choice as the new  focus owner. |
|`addChangeListener()`|addChangeListener|Takes 0 args. Method in interface javax.swing.SpinnerModel  Adds a ChangeListener to the model's listener list. |
|`addLayoutComponent(${1:String}, ${2:Component})`|addLayoutComponent|Takes 2 args. Method in class javax.swing.SpringLayout  Has no effect,  since this layout manager does not  use a per-component string. |
|`addPropertyChangeListener()`|addPropertyChangeListener|Takes 0 args. Method in class javax.swing.SwingWorker  Adds a PropertyChangeListener to the listener list. |
|`addActionListener()`|addActionListener|Takes 0 args. Method in class javax.swing.Timer  Adds an action listener to the Timer. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.ToolTipManager.insideTimerAction  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.ToolTipManager.outsideTimerAction  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.ToolTipManager.stillInsideTimerAction  |
|`addPropertyChangeListener()`|addPropertyChangeListener|Takes 0 args. Method in class javax.swing.UIDefaults  Adds a PropertyChangeListener to the listener list. |
|`addResourceBundle()`|addResourceBundle|Takes 0 args. Method in class javax.swing.UIDefaults  Adds a resource bundle to the list of resource bundles that are  searched for localized values. |
|`addAuxiliaryLookAndFeel()`|addAuxiliaryLookAndFeel|Takes 0 args. Static method in class javax.swing.UIManager  Adds a LookAndFeel to the list of auxiliary look and feels. |
|`addPropertyChangeListener()`|addPropertyChangeListener|Takes 0 args. Static method in class javax.swing.UIManager  Adds a PropertyChangeListener to the listener list. |
|`addLayoutComponent(${1:String}, ${2:Component})`|addLayoutComponent|Takes 2 args. Method in class javax.swing.ViewportLayout  Adds the specified component to the layout. |
|`ABOVE_BOTTOM`|ABOVE_BOTTOM|Takes 0 args. Static variable in class javax.swing.border.TitledBorder  Position the title above the border's bottom line. |
|`ABOVE_TOP`|ABOVE_TOP|Takes 0 args. Static variable in class javax.swing.border.TitledBorder  Position the title above the border's top line. |
|`addChangeListener()`|addChangeListener|Takes 0 args. Method in interface javax.swing.colorchooser.ColorSelectionModel  Adds listener as a listener to changes in the model. |
|`addChangeListener()`|addChangeListener|Takes 0 args. Method in class javax.swing.colorchooser.DefaultColorSelectionModel  Adds a ChangeListener to the model. |
|`ANCESTOR_ADDED`|ANCESTOR_ADDED|Takes 0 args. Static variable in class javax.swing.event.AncestorEvent  An ancestor-component was added to the hierarchy of  visible objects (made visible), and is currently being displayed. |
|`ANCESTOR_MOVED`|ANCESTOR_MOVED|Takes 0 args. Static variable in class javax.swing.event.AncestorEvent  An ancestor-component changed its position on the screen. |
|`ANCESTOR_REMOVED`|ANCESTOR_REMOVED|Takes 0 args. Static variable in class javax.swing.event.AncestorEvent  An ancestor-component was removed from the hierarchy  of visible objects (hidden) and is no longer being displayed. |
|`ancestorAdded()`|ancestorAdded|Takes 0 args. Method in interface javax.swing.event.AncestorListener  Called when the source or one of its ancestors is made visible  either by setVisible(true) being called or by its being  added to the component hierarchy. |
|`ancestorMoved()`|ancestorMoved|Takes 0 args. Method in interface javax.swing.event.AncestorListener  Called when either the source or one of its ancestors is moved. |
|`ancestorRemoved()`|ancestorRemoved|Takes 0 args. Method in interface javax.swing.event.AncestorListener  Called when the source or one of its ancestors is made invisible  either by setVisible(false) being called or by its being  remove from the component hierarchy. |
|`add(${1:Class}, ${2:T})`|add|Takes 2 args. Method in class javax.swing.event.EventListenerList  Adds the listener as a listener of the specified type. |
|`ACTIVATED`|ACTIVATED|Takes 0 args. Static variable in class javax.swing.event.HyperlinkEvent.EventType  Activated type. |
|`ALL_COLUMNS`|ALL_COLUMNS|Takes 0 args. Static variable in class javax.swing.event.TableModelEvent  Specifies all columns in a row or rows. |
|`areNew`|areNew|Takes 0 args. Variable in class javax.swing.event.TreeSelectionEvent  For each path identifies if that path is in fact new. |
|`accept()`|accept|Takes 0 args. Method in class javax.swing.filechooser.FileFilter  Whether the given file is accepted by this filter. |
|`accept()`|accept|Takes 0 args. Method in class javax.swing.filechooser.FileNameExtensionFilter  Tests the specified file, returning true if the file is  accepted, false otherwise. |
|`addPropertyChangeListener(${1:String}, ${2:PropertyChangeListener})`|addPropertyChangeListener|Takes 2 args. Method in class javax.swing.plaf.LayerUI  Adds a PropertyChangeListener to the listener list for a specific  property. |
|`applyPropertyChange(${1:PropertyChangeEvent}, ${2:JLayer})`|applyPropertyChange|Takes 2 args. Method in class javax.swing.plaf.LayerUI  Notifies the LayerUI when any of its property are changed  and enables updating every JLayer  this LayerUI instance is set to. |
|`addActionListener()`|addActionListener|Takes 0 args. Method in class javax.swing.plaf.basic.BasicComboBoxEditor  |
|`addLayoutComponent(${1:String}, ${2:Component})`|addLayoutComponent|Takes 2 args. Method in class javax.swing.plaf.basic.BasicComboBoxUI.ComboBoxLayoutManager  |
|`addEditor()`|addEditor|Takes 0 args. Method in class javax.swing.plaf.basic.BasicComboBoxUI  This public method is implementation specific and should be private. |
|`arrowButton`|arrowButton|Takes 0 args. Variable in class javax.swing.plaf.basic.BasicComboBoxUI  |
|`autoScrollDown()`|autoScrollDown|Takes 0 args. Method in class javax.swing.plaf.basic.BasicComboPopup  This protected method is implementation specific and should be private. |
|`autoScrollUp()`|autoScrollUp|Takes 0 args. Method in class javax.swing.plaf.basic.BasicComboPopup  This protected method is implementation specific and should be private. |
|`autoscrollTimer`|autoscrollTimer|Takes 0 args. Variable in class javax.swing.plaf.basic.BasicComboPopup  This protected field is implementation specific. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicDesktopPaneUI.CloseAction  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicDesktopPaneUI.MaximizeAction  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicDesktopPaneUI.MinimizeAction  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicDesktopPaneUI.NavigateAction  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicDesktopPaneUI.OpenAction  |
|`addPropertyChangeListener()`|addPropertyChangeListener|Takes 0 args. Method in class javax.swing.plaf.basic.BasicDirectoryModel  Adds a PropertyChangeListener to the listener list. |
|`accept()`|accept|Takes 0 args. Method in class javax.swing.plaf.basic.BasicFileChooserUI.AcceptAllFileFilter  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicFileChooserUI.ApproveSelectionAction  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicFileChooserUI.CancelSelectionAction  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicFileChooserUI.ChangeToParentDirectoryAction  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicFileChooserUI.GoHomeAction  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicFileChooserUI.NewFolderAction  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicFileChooserUI.UpdateAction  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicInternalFrameTitlePane.CloseAction  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicInternalFrameTitlePane.IconifyAction  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicInternalFrameTitlePane.MaximizeAction  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicInternalFrameTitlePane.MoveAction  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicInternalFrameTitlePane.RestoreAction  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicInternalFrameTitlePane.SizeAction  |
|`addLayoutComponent(${1:String}, ${2:Component})`|addLayoutComponent|Takes 2 args. Method in class javax.swing.plaf.basic.BasicInternalFrameTitlePane.TitlePaneLayout  |
|`addSubComponents()`|addSubComponents|Takes 0 args. Method in class javax.swing.plaf.basic.BasicInternalFrameTitlePane  |
|`addSystemMenuItems()`|addSystemMenuItems|Takes 0 args. Method in class javax.swing.plaf.basic.BasicInternalFrameTitlePane  |
|`assembleSystemMenu()`|assembleSystemMenu|Takes 0 args. Method in class javax.swing.plaf.basic.BasicInternalFrameTitlePane  |
|`addLayoutComponent(${1:String}, ${2:Component})`|addLayoutComponent|Takes 2 args. Method in class javax.swing.plaf.basic.BasicInternalFrameUI.InternalFrameLayout  |
|`activateFrame()`|activateFrame|Takes 0 args. Method in class javax.swing.plaf.basic.BasicInternalFrameUI  This method is called when the frame becomes selected. |
|`acceleratorDelimiter`|acceleratorDelimiter|Takes 0 args. Variable in class javax.swing.plaf.basic.BasicMenuItemUI  Accelerator delimiter string, such as '+' in 'Ctrl+C'. |
|`acceleratorFont`|acceleratorFont|Takes 0 args. Variable in class javax.swing.plaf.basic.BasicMenuItemUI  |
|`acceleratorForeground`|acceleratorForeground|Takes 0 args. Variable in class javax.swing.plaf.basic.BasicMenuItemUI  |
|`acceleratorSelectionForeground`|acceleratorSelectionForeground|Takes 0 args. Variable in class javax.swing.plaf.basic.BasicMenuItemUI  |
|`arrowIcon`|arrowIcon|Takes 0 args. Variable in class javax.swing.plaf.basic.BasicMenuItemUI  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicOptionPaneUI.ButtonActionListener  |
|`addLayoutComponent(${1:String}, ${2:Component})`|addLayoutComponent|Takes 2 args. Method in class javax.swing.plaf.basic.BasicOptionPaneUI.ButtonAreaLayout  |
|`addButtonComponents(${1:Container}, ${2:Object[]}, ${3:int})`|addButtonComponents|Takes 3 args. Method in class javax.swing.plaf.basic.BasicOptionPaneUI  Creates the appropriate object to represent each of the objects in  buttons and adds it to container. |
|`addIcon()`|addIcon|Takes 0 args. Method in class javax.swing.plaf.basic.BasicOptionPaneUI  Creates and adds a JLabel representing the icon returned from  getIcon to top. |
|`addMessageComponents(${1:Container}, ${2:GridBagConstraints}, ${3:Object}, ${4:int}, ${5:boolean})`|addMessageComponents|Takes 5 args. Method in class javax.swing.plaf.basic.BasicOptionPaneUI  Creates the appropriate object to represent msg and  places it into container. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicScrollBarUI.ScrollListener  |
|`addLayoutComponent(${1:String}, ${2:Component})`|addLayoutComponent|Takes 2 args. Method in class javax.swing.plaf.basic.BasicScrollBarUI  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicSliderUI.ActionScroller  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicSliderUI.ScrollListener  |
|`addLayoutComponent(${1:String}, ${2:Component})`|addLayoutComponent|Takes 2 args. Method in class javax.swing.plaf.basic.BasicSplitPaneDivider.DividerLayout  |
|`addLayoutComponent(${1:String}, ${2:Component})`|addLayoutComponent|Takes 2 args. Method in class javax.swing.plaf.basic.BasicSplitPaneUI.BasicHorizontalLayoutManager  Adds the component at place. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicSplitPaneUI.KeyboardDownRightHandler  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicSplitPaneUI.KeyboardEndHandler  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicSplitPaneUI.KeyboardHomeHandler  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicSplitPaneUI.KeyboardResizeToggleHandler  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicSplitPaneUI.KeyboardUpLeftHandler  |
|`addLayoutComponent(${1:String}, ${2:Component})`|addLayoutComponent|Takes 2 args. Method in class javax.swing.plaf.basic.BasicTabbedPaneUI.TabbedPaneLayout  |
|`assureRectsCreated()`|assureRectsCreated|Takes 0 args. Method in class javax.swing.plaf.basic.BasicTabbedPaneUI  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicTreeUI.ComponentHandler  Public as a result of Timer. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicTreeUI.TreeCancelEditingAction  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicTreeUI.TreeHomeAction  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicTreeUI.TreeIncrementAction  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicTreeUI.TreePageAction  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicTreeUI.TreeToggleAction  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.basic.BasicTreeUI.TreeTraverseAction  |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.plaf.metal.MetalFileChooserUI.DirectoryComboBoxAction  |
|`addControlButtons()`|addControlButtons|Takes 0 args. Method in class javax.swing.plaf.metal.MetalFileChooserUI  |
|`addNotify()`|addNotify|Takes 0 args. Method in class javax.swing.plaf.metal.MetalInternalFrameTitlePane  |
|`addSubComponents()`|addSubComponents|Takes 0 args. Method in class javax.swing.plaf.metal.MetalInternalFrameTitlePane  Override the parent's method avoid creating a menu bar. |
|`addSystemMenuItems()`|addSystemMenuItems|Takes 0 args. Method in class javax.swing.plaf.metal.MetalInternalFrameTitlePane  Override the parent's method to do nothing. |
|`assembleSystemMenu()`|assembleSystemMenu|Takes 0 args. Method in class javax.swing.plaf.metal.MetalInternalFrameTitlePane  Override the parent's method to do nothing. |
|`addCustomEntriesToTable()`|addCustomEntriesToTable|Takes 0 args. Method in class javax.swing.plaf.metal.MetalTheme  Adds values specific to this theme to the defaults table. |
|`addCustomEntriesToTable()`|addCustomEntriesToTable|Takes 0 args. Method in class javax.swing.plaf.metal.OceanTheme  Add this theme's custom entries to the defaults table. |
|`ARROW_BUTTON`|ARROW_BUTTON|Takes 0 args. Static variable in class javax.swing.plaf.synth.Region  ArrowButton's are special types of buttons that also render a  directional indicator, typically an arrow. |
|`addTableModelListener()`|addTableModelListener|Takes 0 args. Method in class javax.swing.table.AbstractTableModel  Adds a listener to the list that's notified each time a change  to the data model occurs. |
|`addColumn()`|addColumn|Takes 0 args. Method in class javax.swing.table.DefaultTableColumnModel  Appends aColumn to the end of the   tableColumns array. |
|`addColumnModelListener()`|addColumnModelListener|Takes 0 args. Method in class javax.swing.table.DefaultTableColumnModel  Adds a listener for table column model events. |
|`addColumn(${1:Object}, ${2:Vector})`|addColumn|Takes 2 args. Method in class javax.swing.table.DefaultTableModel  Adds a column to the model. |
|`addRow()`|addRow|Takes 0 args. Method in class javax.swing.table.DefaultTableModel  Adds a row to the end of the model. |
|`addFocusListener()`|addFocusListener|Takes 0 args. Method in class javax.swing.table.JTableHeader.AccessibleJTableHeader.AccessibleJTableHeaderEntry  |
|`addPropertyChangeListener()`|addPropertyChangeListener|Takes 0 args. Method in class javax.swing.table.JTableHeader.AccessibleJTableHeader.AccessibleJTableHeaderEntry  |
|`addPropertyChangeListener()`|addPropertyChangeListener|Takes 0 args. Method in class javax.swing.table.TableColumn  Adds a PropertyChangeListener to the listener list. |
|`addColumn()`|addColumn|Takes 0 args. Method in interface javax.swing.table.TableColumnModel  Appends aColumn to the end of the   tableColumns array. |
|`addColumnModelListener()`|addColumnModelListener|Takes 0 args. Method in interface javax.swing.table.TableColumnModel  Adds a listener for table column model events. |
|`addTableModelListener()`|addTableModelListener|Takes 0 args. Method in interface javax.swing.table.TableModel  Adds a listener to the list that is notified each time a change  to the data model occurs. |
|`addAttribute(${1:Object}, ${2:Object})`|addAttribute|Takes 2 args. Method in class javax.swing.text.AbstractDocument.AbstractElement  Adds an attribute to the element. |
|`addAttributes()`|addAttributes|Takes 0 args. Method in class javax.swing.text.AbstractDocument.AbstractElement  Adds a set of attributes to the element. |
|`addAttribute(${1:AttributeSet}, ${2:Object}, ${3:Object})`|addAttribute|Takes 3 args. Method in interface javax.swing.text.AbstractDocument.AttributeContext  Adds an attribute to the given set, and returns  the new representative set. |
|`addAttributes(${1:AttributeSet}, ${2:AttributeSet})`|addAttributes|Takes 2 args. Method in interface javax.swing.text.AbstractDocument.AttributeContext  Adds a set of attributes to the element. |
|`addEdit()`|addEdit|Takes 0 args. Method in class javax.swing.text.AbstractDocument.DefaultDocumentEvent  Adds a document edit. |
|`addDocumentListener()`|addDocumentListener|Takes 0 args. Method in class javax.swing.text.AbstractDocument  Adds a document listener for notification of any changes. |
|`addUndoableEditListener()`|addUndoableEditListener|Takes 0 args. Method in class javax.swing.text.AbstractDocument  Adds an undo listener for notification of any changes. |
|`addChangeListener()`|addChangeListener|Takes 0 args. Method in interface javax.swing.text.Caret  Adds a listener to track whenever the caret position  has been changed. |
|`ALWAYS_UPDATE`|ALWAYS_UPDATE|Takes 0 args. Static variable in class javax.swing.text.DefaultCaret  Indicates that the caret position is to be always  updated accordingly to the document changes regardless whether  the document updates are performed on the Event Dispatching Thread  or not. |
|`addChangeListener()`|addChangeListener|Takes 0 args. Method in class javax.swing.text.DefaultCaret  Adds a listener to track whenever the caret position has  been changed. |
|`adjustVisibility()`|adjustVisibility|Takes 0 args. Method in class javax.swing.text.DefaultCaret  Scrolls the associated view (if necessary) to make  the caret visible. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.text.DefaultEditorKit.BeepAction  The operation to perform when this action is triggered. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.text.DefaultEditorKit.CopyAction  The operation to perform when this action is triggered. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.text.DefaultEditorKit.CutAction  The operation to perform when this action is triggered. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.text.DefaultEditorKit.DefaultKeyTypedAction  The operation to perform when this action is triggered. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.text.DefaultEditorKit.InsertBreakAction  The operation to perform when this action is triggered. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.text.DefaultEditorKit.InsertContentAction  The operation to perform when this action is triggered. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.text.DefaultEditorKit.InsertTabAction  The operation to perform when this action is triggered. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.text.DefaultEditorKit.PasteAction  The operation to perform when this action is triggered. |
|`addHighlight(${1:int}, ${2:int}, ${3:Highlighter.HighlightPainter})`|addHighlight|Takes 3 args. Method in class javax.swing.text.DefaultHighlighter  Adds a highlight to the view. |
|`addDocumentListener()`|addDocumentListener|Takes 0 args. Method in class javax.swing.text.DefaultStyledDocument  Adds a document listener for notification of any changes. |
|`addStyle(${1:String}, ${2:Style})`|addStyle|Takes 2 args. Method in class javax.swing.text.DefaultStyledDocument  Adds a new style into the logical style hierarchy. |
|`addDocumentListener()`|addDocumentListener|Takes 0 args. Method in interface javax.swing.text.Document  Registers the given observer to begin receiving notifications  when changes are made to the document. |
|`addUndoableEditListener()`|addUndoableEditListener|Takes 0 args. Method in interface javax.swing.text.Document  Registers the given observer to begin receiving notifications  when undoable edits are made to the document. |
|`adjustAllocation()`|adjustAllocation|Takes 0 args. Method in class javax.swing.text.FieldView  Adjusts the allocation given to the view  to be a suitable allocation for a text field. |
|`adjustRow(${1:FlowView}, ${2:int}, ${3:int}, ${4:int})`|adjustRow|Takes 4 args. Method in class javax.swing.text.FlowView.FlowStrategy  Adjusts the given row if possible to fit within the  layout span. |
|`allocateArray()`|allocateArray|Takes 0 args. Method in class javax.swing.text.GapContent  Allocate an array to store items of the type  appropriate (which is determined by the subclass). |
|`addHighlight(${1:int}, ${2:int}, ${3:Highlighter.HighlightPainter})`|addHighlight|Takes 3 args. Method in interface javax.swing.text.Highlighter  Adds a highlight to the view. |
|`actionName`|actionName|Takes 0 args. Variable in class javax.swing.text.JTextComponent.KeyBinding  The name of the action for the key. |
|`addCaretListener()`|addCaretListener|Takes 0 args. Method in class javax.swing.text.JTextComponent  Adds a caret listener for notification of any changes  to the caret. |
|`addInputMethodListener()`|addInputMethodListener|Takes 0 args. Method in class javax.swing.text.JTextComponent  |
|`addKeymap(${1:String}, ${2:Keymap})`|addKeymap|Takes 2 args. Static method in class javax.swing.text.JTextComponent  Adds a new keymap into the keymap hierarchy. |
|`addActionForKeyStroke(${1:KeyStroke}, ${2:Action})`|addActionForKeyStroke|Takes 2 args. Method in interface javax.swing.text.Keymap  Adds a binding to the keymap. |
|`addTask()`|addTask|Takes 0 args. Method in class javax.swing.text.LayoutQueue  Add a task that is not needed immediately because  the results are not believed to be visible. |
|`addAttribute(${1:Object}, ${2:Object})`|addAttribute|Takes 2 args. Method in interface javax.swing.text.MutableAttributeSet  Creates a new attribute set similar to this one except that it contains  an attribute with the given name and value. |
|`addAttributes()`|addAttributes|Takes 0 args. Method in interface javax.swing.text.MutableAttributeSet  Creates a new attribute set similar to this one except that it contains  the given attributes and values. |
|`array`|array|Takes 0 args. Variable in class javax.swing.text.Segment  This is the array containing the text of  interest. |
|`addAttribute(${1:Object}, ${2:Object})`|addAttribute|Takes 2 args. Method in class javax.swing.text.SimpleAttributeSet  Adds an attribute to the list. |
|`addAttributes()`|addAttributes|Takes 0 args. Method in class javax.swing.text.SimpleAttributeSet  Adds a set of attributes to the list. |
|`addChangeListener()`|addChangeListener|Takes 0 args. Method in interface javax.swing.text.Style  Adds a listener to track whenever an attribute  has been changed. |
|`ALIGN_CENTER`|ALIGN_CENTER|Takes 0 args. Static variable in class javax.swing.text.StyleConstants  A possible value for paragraph alignment. |
|`ALIGN_JUSTIFIED`|ALIGN_JUSTIFIED|Takes 0 args. Static variable in class javax.swing.text.StyleConstants  A possible value for paragraph alignment. |
|`ALIGN_LEFT`|ALIGN_LEFT|Takes 0 args. Static variable in class javax.swing.text.StyleConstants  A possible value for paragraph alignment. |
|`ALIGN_RIGHT`|ALIGN_RIGHT|Takes 0 args. Static variable in class javax.swing.text.StyleConstants  A possible value for paragraph alignment. |
|`Alignment`|Alignment|Takes 0 args. Static variable in class javax.swing.text.StyleConstants  Alignment for the paragraph. |
|`addAttribute(${1:Object}, ${2:Object})`|addAttribute|Takes 2 args. Method in class javax.swing.text.StyleContext.NamedStyle  Adds an attribute. |
|`addAttributes()`|addAttributes|Takes 0 args. Method in class javax.swing.text.StyleContext.NamedStyle  Adds a set of attributes to the element. |
|`addChangeListener()`|addChangeListener|Takes 0 args. Method in class javax.swing.text.StyleContext.NamedStyle  Adds a change listener. |
|`addAttribute(${1:AttributeSet}, ${2:Object}, ${3:Object})`|addAttribute|Takes 3 args. Method in class javax.swing.text.StyleContext  Adds an attribute to the given set, and returns  the new representative set. |
|`addAttributes(${1:AttributeSet}, ${2:AttributeSet})`|addAttributes|Takes 2 args. Method in class javax.swing.text.StyleContext  Adds a set of attributes to the element. |
|`addChangeListener()`|addChangeListener|Takes 0 args. Method in class javax.swing.text.StyleContext  Adds a listener to track when styles are added  or removed. |
|`addStyle(${1:String}, ${2:Style})`|addStyle|Takes 2 args. Method in class javax.swing.text.StyleContext  Adds a new style into the style hierarchy. |
|`addStyle(${1:String}, ${2:Style})`|addStyle|Takes 2 args. Method in interface javax.swing.text.StyledDocument  Adds a new style into the logical style hierarchy. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.text.StyledEditorKit.AlignmentAction  Sets the alignment. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.text.StyledEditorKit.BoldAction  Toggles the bold attribute. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.text.StyledEditorKit.FontFamilyAction  Sets the font family. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.text.StyledEditorKit.FontSizeAction  Sets the font size. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.text.StyledEditorKit.ForegroundAction  Sets the foreground color. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.text.StyledEditorKit.ItalicAction  Toggles the italic attribute. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.text.StyledEditorKit.UnderlineAction  Toggles the Underline attribute. |
|`ALIGN_BAR`|ALIGN_BAR|Takes 0 args. Static variable in class javax.swing.text.TabStop  |
|`ALIGN_CENTER`|ALIGN_CENTER|Takes 0 args. Static variable in class javax.swing.text.TabStop  Characters following tab are positioned such that all following  characters up to next tab/newline are centered around the tabs  location. |
|`ALIGN_DECIMAL`|ALIGN_DECIMAL|Takes 0 args. Static variable in class javax.swing.text.TabStop  Characters following tab are aligned such that next  decimal/tab/newline is at the tab location, very similar to  RIGHT_TAB, just includes decimal as additional character to look for. |
|`ALIGN_LEFT`|ALIGN_LEFT|Takes 0 args. Static variable in class javax.swing.text.TabStop  Character following tab is positioned at location. |
|`ALIGN_RIGHT`|ALIGN_RIGHT|Takes 0 args. Static variable in class javax.swing.text.TabStop  Characters following tab are positioned such that all following  characters up to next tab/newline end at location. |
|`augmentList(${1:Action[]}, ${2:Action[]})`|augmentList|Takes 2 args. Static method in class javax.swing.text.TextAction  Takes one list of  commands and augments it with another list  of commands. |
|`append()`|append|Takes 0 args. Method in class javax.swing.text.View  Appends a single child view. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.text.html.FormView  Responsible for processing the ActionEvent. |
|`ACTION`|ACTION|Takes 0 args. Static variable in class javax.swing.text.html.HTML.Attribute  |
|`ALIGN`|ALIGN|Takes 0 args. Static variable in class javax.swing.text.html.HTML.Attribute  |
|`ALINK`|ALINK|Takes 0 args. Static variable in class javax.swing.text.html.HTML.Attribute  |
|`ALT`|ALT|Takes 0 args. Static variable in class javax.swing.text.html.HTML.Attribute  |
|`ARCHIVE`|ARCHIVE|Takes 0 args. Static variable in class javax.swing.text.html.HTML.Attribute  |
|`ADDRESS`|ADDRESS|Takes 0 args. Static variable in class javax.swing.text.html.HTML.Tag  |
|`APPLET`|APPLET|Takes 0 args. Static variable in class javax.swing.text.html.HTML.Tag  |
|`AREA`|AREA|Takes 0 args. Static variable in class javax.swing.text.html.HTML.Tag  |
|`addContent(${1:char[]}, ${2:int}, ${3:int}, ${4:boolean})`|addContent|Takes 4 args. Method in class javax.swing.text.html.HTMLDocument.HTMLReader  Adds some text with the current character attributes. |
|`addSpecialElement(${1:HTML.Tag}, ${2:MutableAttributeSet})`|addSpecialElement|Takes 2 args. Method in class javax.swing.text.html.HTMLDocument.HTMLReader  Adds content that is basically specified entirely  in the attribute set. |
|`AdditionalComments`|AdditionalComments|Takes 0 args. Static variable in class javax.swing.text.html.HTMLDocument  Document property key value. |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.text.html.HTMLEditorKit.InsertHTMLTextAction  Inserts the HTML into the document. |
|`addTag`|addTag|Takes 0 args. Variable in class javax.swing.text.html.HTMLEditorKit.InsertHTMLTextAction  Tag in HTML to start adding tags from. |
|`alternateAddTag`|alternateAddTag|Takes 0 args. Variable in class javax.swing.text.html.HTMLEditorKit.InsertHTMLTextAction  Alternate tag in HTML to start adding tags from if parentTag  is not found and alternateParentTag is found. |
|`alternateParentTag`|alternateParentTag|Takes 0 args. Variable in class javax.swing.text.html.HTMLEditorKit.InsertHTMLTextAction  Alternate Tag to check for in the document if parentTag is  not found. |
|`activateLink(${1:int}, ${2:JEditorPane})`|activateLink|Takes 2 args. Method in class javax.swing.text.html.HTMLEditorKit.LinkController  Calls linkActivated on the associated JEditorPane  if the given position represents a link. |
|`addAttribute(${1:AttributeSet}, ${2:Object}, ${3:Object})`|addAttribute|Takes 3 args. Method in class javax.swing.text.html.StyleSheet  Adds an attribute to the given set, and returns  the new representative set. |
|`addAttributes(${1:AttributeSet}, ${2:AttributeSet})`|addAttributes|Takes 2 args. Method in class javax.swing.text.html.StyleSheet  Adds a set of attributes to the element. |
|`addCSSAttribute(${1:MutableAttributeSet}, ${2:CSS.Attribute}, ${3:String})`|addCSSAttribute|Takes 3 args. Method in class javax.swing.text.html.StyleSheet  Adds a CSS attribute to the given set. |
|`addCSSAttributeFromHTML(${1:MutableAttributeSet}, ${2:CSS.Attribute}, ${3:String})`|addCSSAttributeFromHTML|Takes 3 args. Method in class javax.swing.text.html.StyleSheet  Adds a CSS attribute to the given set. |
|`addRule()`|addRule|Takes 0 args. Method in class javax.swing.text.html.StyleSheet  Adds a set of rules to the sheet. |
|`addStyleSheet()`|addStyleSheet|Takes 0 args. Method in class javax.swing.text.html.StyleSheet  Adds the rules from the StyleSheet ss to those of  the receiver. |
|`applet`|applet|Takes 0 args. Variable in class javax.swing.text.html.parser.DTD  |
|`ANY`|ANY|Takes 0 args. Static variable in interface javax.swing.text.html.parser.DTDConstants  |
|`atts`|atts|Takes 0 args. Variable in class javax.swing.text.html.parser.Element  |
|`add()`|add|Takes 0 args. Method in class javax.swing.tree.DefaultMutableTreeNode  Removes newChild from its parent and makes it a child of  this node by adding it to the end of this node's child array. |
|`allowsChildren`|allowsChildren|Takes 0 args. Variable in class javax.swing.tree.DefaultMutableTreeNode  true if the node is able to have children |
|`actionPerformed()`|actionPerformed|Takes 0 args. Method in class javax.swing.tree.DefaultTreeCellEditor  Messaged when the timer fires, this will start the editing  session. |
|`addCellEditorListener()`|addCellEditorListener|Takes 0 args. Method in class javax.swing.tree.DefaultTreeCellEditor  Adds the CellEditorListener. |
|`addTreeModelListener()`|addTreeModelListener|Takes 0 args. Method in class javax.swing.tree.DefaultTreeModel  Adds a listener for the TreeModelEvent posted after the tree changes. |
|`asksAllowsChildren`|asksAllowsChildren|Takes 0 args. Variable in class javax.swing.tree.DefaultTreeModel  Determines how the isLeaf method figures  out if a node is a leaf node. |
|`asksAllowsChildren()`|asksAllowsChildren|Takes 0 args. Method in class javax.swing.tree.DefaultTreeModel  Tells how leaf nodes are determined. |
|`addPropertyChangeListener()`|addPropertyChangeListener|Takes 0 args. Method in class javax.swing.tree.DefaultTreeSelectionModel  Adds a PropertyChangeListener to the listener list. |
|`addSelectionPath()`|addSelectionPath|Takes 0 args. Method in class javax.swing.tree.DefaultTreeSelectionModel  Adds path to the current selection. |
|`addSelectionPaths()`|addSelectionPaths|Takes 0 args. Method in class javax.swing.tree.DefaultTreeSelectionModel  Adds paths to the current selection. |
|`addTreeSelectionListener()`|addTreeSelectionListener|Takes 0 args. Method in class javax.swing.tree.DefaultTreeSelectionModel  Adds x to the list of listeners that are notified each time the  set of selected TreePaths changes. |
|`arePathsContiguous()`|arePathsContiguous|Takes 0 args. Method in class javax.swing.tree.DefaultTreeSelectionModel  Returns true if the paths are contiguous,  or this object has no RowMapper. |
|`addTreeModelListener()`|addTreeModelListener|Takes 0 args. Method in interface javax.swing.tree.TreeModel  Adds a listener for the TreeModelEvent  posted after the tree changes. |
|`addPropertyChangeListener()`|addPropertyChangeListener|Takes 0 args. Method in interface javax.swing.tree.TreeSelectionModel  Adds a PropertyChangeListener to the listener list. |
|`addSelectionPath()`|addSelectionPath|Takes 0 args. Method in interface javax.swing.tree.TreeSelectionModel  Adds path to the current selection. |
|`addSelectionPaths()`|addSelectionPaths|Takes 0 args. Method in interface javax.swing.tree.TreeSelectionModel  Adds paths to the current selection. |
|`addTreeSelectionListener()`|addTreeSelectionListener|Takes 0 args. Method in interface javax.swing.tree.TreeSelectionModel  Adds x to the list of listeners that are notified each time the  set of selected TreePaths changes. |
|`addEdit()`|addEdit|Takes 0 args. Method in class javax.swing.undo.AbstractUndoableEdit  This default implementation returns false. |
|`addEdit()`|addEdit|Takes 0 args. Method in class javax.swing.undo.CompoundEdit  If this edit is inProgress,  accepts anEdit and returns true. |
|`addEdit()`|addEdit|Takes 0 args. Method in class javax.swing.undo.UndoManager  Adds an UndoableEdit to this  UndoManager, if it's possible. |
|`addEdit()`|addEdit|Takes 0 args. Method in interface javax.swing.undo.UndoableEdit  Adds an UndoableEdit to this UndoableEdit. |
|`addUndoableEditListener()`|addUndoableEditListener|Takes 0 args. Method in class javax.swing.undo.UndoableEditSupport  Registers an UndoableEditListener. |
|`ACCESS_EXTERNAL_DTD`|ACCESS_EXTERNAL_DTD|Takes 0 args. Static variable in class javax.xml.XMLConstants  Property: accessExternalDTD |
|`ACCESS_EXTERNAL_SCHEMA`|ACCESS_EXTERNAL_SCHEMA|Takes 0 args. Static variable in class javax.xml.XMLConstants  Property: accessExternalSchema |
|`ACCESS_EXTERNAL_STYLESHEET`|ACCESS_EXTERNAL_STYLESHEET|Takes 0 args. Static variable in class javax.xml.XMLConstants  Property: accessExternalStylesheet |
|`afterMarshal()`|afterMarshal|Takes 0 args. Method in class javax.xml.bind.Marshaller.Listener    Callback method invoked after marshalling source to XML. |
|`afterUnmarshal(${1:Object}, ${2:Object})`|afterUnmarshal|Takes 2 args. Method in class javax.xml.bind.Unmarshaller.Listener    Callback method invoked after unmarshalling XML data into target. |
|`addMtomAttachment(${1:DataHandler}, ${2:String}, ${3:String})`|addMtomAttachment|Takes 3 args. Method in class javax.xml.bind.attachment.AttachmentMarshaller  Consider MIME content data for optimized binary storage as an attachment. |
|`addSwaRefAttachment()`|addSwaRefAttachment|Takes 0 args. Method in class javax.xml.bind.attachment.AttachmentMarshaller  Add MIME data as an attachment and return attachment's content-id, cid. |
|`APRIL`|APRIL|Takes 0 args. Static variable in class javax.xml.datatype.DatatypeConstants  Value for fourth month of year. |
|`AUGUST`|AUGUST|Takes 0 args. Static variable in class javax.xml.datatype.DatatypeConstants  Value for eighth month of year. |
|`add()`|add|Takes 0 args. Method in class javax.xml.datatype.Duration  Computes a new duration whose value is this+rhs. |
|`addTo()`|addTo|Takes 0 args. Method in class javax.xml.datatype.Duration  Adds this duration to a Date object. |
|`add()`|add|Takes 0 args. Method in class javax.xml.datatype.XMLGregorianCalendar  Add duration to this instance. |
|`addMimeHeader(${1:String}, ${2:String})`|addMimeHeader|Takes 2 args. Method in class javax.xml.soap.AttachmentPart  Adds a MIME header with the specified name and value to this  AttachmentPart object. |
|`addDetailEntry()`|addDetailEntry|Takes 0 args. Method in interface javax.xml.soap.Detail  Creates a new DetailEntry object with the given  name and adds it to this Detail object. |
|`addHeader(${1:String}, ${2:String})`|addHeader|Takes 2 args. Method in class javax.xml.soap.MimeHeaders  Adds a MimeHeader object with the specified name and value  to this MimeHeaders object's list of headers. |
|`addBodyElement()`|addBodyElement|Takes 0 args. Method in interface javax.xml.soap.SOAPBody  Creates a new SOAPBodyElement object with the specified  name and adds it to this SOAPBody object. |
|`addDocument()`|addDocument|Takes 0 args. Method in interface javax.xml.soap.SOAPBody  Adds the root node of the DOM Document  to this SOAPBody object. |
|`addFault(${1:Name}, ${2:String}, ${3:Locale})`|addFault|Takes 3 args. Method in interface javax.xml.soap.SOAPBody  Creates a new SOAPFault object and adds it to  this SOAPBody object. |
|`addAttribute(${1:Name}, ${2:String})`|addAttribute|Takes 2 args. Method in interface javax.xml.soap.SOAPElement  Adds an attribute with the specified name and value to this  SOAPElement object. |
|`addChildElement()`|addChildElement|Takes 0 args. Method in interface javax.xml.soap.SOAPElement  Add a SOAPElement as a child of this  SOAPElement instance. |
|`addNamespaceDeclaration(${1:String}, ${2:String})`|addNamespaceDeclaration|Takes 2 args. Method in interface javax.xml.soap.SOAPElement  Adds a namespace declaration with the specified prefix and URI to this  SOAPElement object. |
|`addTextNode()`|addTextNode|Takes 0 args. Method in interface javax.xml.soap.SOAPElement  Creates a new Text object initialized with the given  String and adds it to this SOAPElement object. |
|`addBody()`|addBody|Takes 0 args. Method in interface javax.xml.soap.SOAPEnvelope  Creates a SOAPBody object and sets it as the  SOAPBody object for this SOAPEnvelope  object. |
|`addHeader()`|addHeader|Takes 0 args. Method in interface javax.xml.soap.SOAPEnvelope  Creates a SOAPHeader object and sets it as the  SOAPHeader object for this SOAPEnvelope  object. |
|`addDetail()`|addDetail|Takes 0 args. Method in interface javax.xml.soap.SOAPFault  Creates an optional Detail object and sets it as the  Detail object for this SOAPFault  object. |
|`addFaultReasonText(${1:String}, ${2:Locale})`|addFaultReasonText|Takes 2 args. Method in interface javax.xml.soap.SOAPFault  Appends or replaces a Reason Text item containing the specified  text message and an xml:lang derived from  locale. |
|`appendFaultSubcode()`|appendFaultSubcode|Takes 0 args. Method in interface javax.xml.soap.SOAPFault  Adds a Subcode to the end of the sequence of Subcodes contained by this  SOAPFault. |
|`addHeaderElement()`|addHeaderElement|Takes 0 args. Method in interface javax.xml.soap.SOAPHeader  Creates a new SOAPHeaderElement object initialized with the  specified name and adds it to this SOAPHeader object. |
|`addNotUnderstoodHeaderElement()`|addNotUnderstoodHeaderElement|Takes 0 args. Method in interface javax.xml.soap.SOAPHeader  Creates a new NotUnderstood SOAPHeaderElement object initialized  with the specified name and adds it to this SOAPHeader object. |
|`addUpgradeHeaderElement()`|addUpgradeHeaderElement|Takes 0 args. Method in interface javax.xml.soap.SOAPHeader  Creates a new Upgrade SOAPHeaderElement object initialized  with the specified List of supported SOAP URIs and adds it to this  SOAPHeader object. |
|`addAttachmentPart()`|addAttachmentPart|Takes 0 args. Method in class javax.xml.soap.SOAPMessage  Adds the given AttachmentPart object to this SOAPMessage  object. |
|`addMimeHeader(${1:String}, ${2:String})`|addMimeHeader|Takes 2 args. Method in class javax.xml.soap.SOAPPart  Creates a MimeHeader object with the specified  name and value and adds it to this SOAPPart object. |
|`accept()`|accept|Takes 0 args. Method in interface javax.xml.stream.EventFilter  Tests whether this event is part of this stream. |
|`accept()`|accept|Takes 0 args. Method in interface javax.xml.stream.StreamFilter  Tests whether the current state is part of this stream. |
|`add()`|add|Takes 0 args. Method in interface javax.xml.stream.XMLEventWriter  Add an event to the output stream  Adding a START_ELEMENT will open a new namespace scope that  will be closed when the corresponding END_ELEMENT is written. |
|`ALLOCATOR`|ALLOCATOR|Takes 0 args. Static variable in class javax.xml.stream.XMLInputFactory  The property used to set/get the implementation of the allocator |
|`ATTRIBUTE`|ATTRIBUTE|Takes 0 args. Static variable in interface javax.xml.stream.XMLStreamConstants  Indicates an event is an attribute |
|`asCharacters()`|asCharacters|Takes 0 args. Method in interface javax.xml.stream.events.XMLEvent  Returns this event as Characters, may result in  a class cast exception if this event is not Characters. |
|`asEndElement()`|asEndElement|Takes 0 args. Method in interface javax.xml.stream.events.XMLEvent  Returns this event as an end  element event, may result in  a class cast exception if this event is not a end element. |
|`asStartElement()`|asStartElement|Takes 0 args. Method in interface javax.xml.stream.events.XMLEvent  Returns this event as a start element event, may result in  a class cast exception if this event is not a start element. |
|`allocate(${1:XMLStreamReader}, ${2:XMLEventConsumer})`|allocate|Takes 2 args. Method in interface javax.xml.stream.util.XMLEventAllocator  This method allocates an event or set of events  given the current  state of the XMLStreamReader and adds the event  or set of events to the  consumer that was passed in. |
|`add()`|add|Takes 0 args. Method in interface javax.xml.stream.util.XMLEventConsumer  This method adds an event to the consumer. |
|`addPort(${1:QName}, ${2:String}, ${3:String})`|addPort|Takes 3 args. Method in class javax.xml.ws.Service  Creates a new port for the service. |
|`addPort(${1:QName}, ${2:String}, ${3:String})`|addPort|Takes 3 args. Method in class javax.xml.ws.spi.ServiceDelegate  Creates a new port for the service. |
|`addResponseHeader(${1:String}, ${2:String})`|addResponseHeader|Takes 2 args. Method in class javax.xml.ws.spi.http.HttpExchange  Adds a response header with the given name and value. |
|`address()`|address|Takes 0 args. Method in class javax.xml.ws.wsaddressing.W3CEndpointReferenceBuilder  Sets the address to the  W3CEndpointReference instance's  wsa:Address. |
|`attribute(${1:QName}, ${2:String})`|attribute|Takes 2 args. Method in class javax.xml.ws.wsaddressing.W3CEndpointReferenceBuilder  Adds an extension attribute to the  W3CEndpointReference instance's  wsa:EndpointReference element. |
|`acceptSecContext(${1:InputStream}, ${2:OutputStream})`|acceptSecContext|Takes 2 args. Method in interface org.ietf.jgss.GSSContext  Called by the context acceptor to process a token from the peer using  streams. |
|`ACCEPT_ONLY`|ACCEPT_ONLY|Takes 0 args. Static variable in interface org.ietf.jgss.GSSCredential  Credential usage flag requesting that it be usable  for context acceptance only. |
|`add(${1:GSSName}, ${2:int}, ${3:int}, ${4:Oid}, ${5:int})`|add|Takes 5 args. Method in interface org.ietf.jgss.GSSCredential  Adds a mechanism specific credential-element to an existing  credential. |
|`addProviderAtEnd(${1:Provider}, ${2:Oid})`|addProviderAtEnd|Takes 2 args. Method in class org.ietf.jgss.GSSManager  This method is used to indicate to the GSSManager that the  application would like a particular provider to be used if no other  provider can be found that supports the given mechanism. |
|`addProviderAtFront(${1:Provider}, ${2:Oid})`|addProviderAtFront|Takes 2 args. Method in class org.ietf.jgss.GSSManager  This method is used to indicate to the GSSManager that the  application would like a particular provider to be used ahead of all  others when support is desired for the given mechanism. |
|`add()`|add|Takes 0 args. Method in class org.omg.CORBA.ContextList  Adds a String object to this ContextList  object. |
|`add()`|add|Takes 0 args. Method in class org.omg.CORBA.ExceptionList  Adds a TypeCode object describing an exception  to this ExceptionList object. |
|`add()`|add|Takes 0 args. Method in class org.omg.CORBA.NVList  Creates a new NamedValue object initialized with the given flag  and adds it to the end of this NVList object. |
|`add_item(${1:String}, ${2:int})`|add_item|Takes 2 args. Method in class org.omg.CORBA.NVList  Creates a new NamedValue object initialized with the  given name and flag,  and adds it to the end of this NVList object. |
|`add_value(${1:String}, ${2:Any}, ${3:int})`|add_value|Takes 3 args. Method in class org.omg.CORBA.NVList  Creates a new NamedValue object initialized with the  given name, value, and flag,  and adds it to the end of this NVList object. |
|`add_in_arg()`|add_in_arg|Takes 0 args. Method in class org.omg.CORBA.Request  Creates an input argument and adds it to this Request  object. |
|`add_inout_arg()`|add_inout_arg|Takes 0 args. Method in class org.omg.CORBA.Request  Adds an input/output argument to this Request object. |
|`add_named_in_arg()`|add_named_in_arg|Takes 0 args. Method in class org.omg.CORBA.Request  Creates an input argument with the given name and adds it to  this Request object. |
|`add_named_inout_arg()`|add_named_inout_arg|Takes 0 args. Method in class org.omg.CORBA.Request  Adds an input/output argument with the given name to this  Request object. |
|`add_named_out_arg()`|add_named_out_arg|Takes 0 args. Method in class org.omg.CORBA.Request  Adds an output argument with the given name to this  Request object. |
|`add_out_arg()`|add_out_arg|Takes 0 args. Method in class org.omg.CORBA.Request  Adds an output argument to this Request object. |
|`arguments()`|arguments|Takes 0 args. Method in class org.omg.CORBA.Request  Retrieves the NVList object containing the arguments  to the method being invoked. |
|`arguments()`|arguments|Takes 0 args. Method in class org.omg.CORBA.ServerRequest  Specifies method parameter types and retrieves "in" and "inout"  argument values. |
|`ADD_OVERRIDE`|ADD_OVERRIDE|Takes 0 args. Static variable in class org.omg.CORBA.SetOverrideType  The SetOverrideType constant for the enum value ADD_OVERRIDE. |
|`access`|access|Takes 0 args. Variable in class org.omg.CORBA.ValueMember  The type of access (public, private) for the value  member described by this ValueMember object. |
|`argument`|argument|Takes 0 args. Variable in class org.omg.Dynamic.Parameter  |
|`assign()`|assign|Takes 0 args. Method in interface org.omg.DynamicAny.DynAnyOperations  Initializes the value associated with a DynAny object with the value  associated with another DynAny object. |
|`assign()`|assign|Takes 0 args. Method in class org.omg.DynamicAny._DynAnyStub  Initializes the value associated with a DynAny object with the value  associated with another DynAny object. |
|`assign()`|assign|Takes 0 args. Method in class org.omg.DynamicAny._DynArrayStub  Initializes the value associated with a DynAny object with the value  associated with another DynAny object. |
|`assign()`|assign|Takes 0 args. Method in class org.omg.DynamicAny._DynEnumStub  Initializes the value associated with a DynAny object with the value  associated with another DynAny object. |
|`assign()`|assign|Takes 0 args. Method in class org.omg.DynamicAny._DynFixedStub  Initializes the value associated with a DynAny object with the value  associated with another DynAny object. |
|`assign()`|assign|Takes 0 args. Method in class org.omg.DynamicAny._DynSequenceStub  Initializes the value associated with a DynAny object with the value  associated with another DynAny object. |
|`assign()`|assign|Takes 0 args. Method in class org.omg.DynamicAny._DynStructStub  Initializes the value associated with a DynAny object with the value  associated with another DynAny object. |
|`assign()`|assign|Takes 0 args. Method in class org.omg.DynamicAny._DynUnionStub  Initializes the value associated with a DynAny object with the value  associated with another DynAny object. |
|`assign()`|assign|Takes 0 args. Method in class org.omg.DynamicAny._DynValueStub  Initializes the value associated with a DynAny object with the value  associated with another DynAny object. |
|`add_request_service_context(${1:ServiceContext}, ${2:boolean})`|add_request_service_context|Takes 2 args. Method in interface org.omg.PortableInterceptor.ClientRequestInfoOperations  Allows Interceptors to add service contexts to the request. |
|`adapter_template()`|adapter_template|Takes 0 args. Method in interface org.omg.PortableInterceptor.IORInfoOperations  Return the object reference template of the object adapter  that was just created and is running IOR interceptors. |
|`add_ior_component()`|add_ior_component|Takes 0 args. Method in interface org.omg.PortableInterceptor.IORInfoOperations  A portable ORB service implementation calls   add_ior_component from its implementation of   establish_components to add a tagged component to the   set which will be included when constructing IORs. |
|`add_ior_component_to_profile(${1:TaggedComponent}, ${2:int})`|add_ior_component_to_profile|Takes 2 args. Method in interface org.omg.PortableInterceptor.IORInfoOperations  A portable ORB service implementation calls   add_ior_component_to_profile from its implementation of   establish_components to add a tagged component to the   set which will be included when constructing IORs. |
|`adapter_manager_state_changed(${1:int}, ${2:short})`|adapter_manager_state_changed|Takes 2 args. Method in interface org.omg.PortableInterceptor.IORInterceptor_3_0Operations  Called whenever the state of an adapter manager changes. |
|`adapter_state_changed(${1:ObjectReferenceTemplate[]}, ${2:short})`|adapter_state_changed|Takes 2 args. Method in interface org.omg.PortableInterceptor.IORInterceptor_3_0Operations  Called whenever the state of an object adapter changes, and  the state change is not caused by an adapter manager. |
|`add_client_request_interceptor()`|add_client_request_interceptor|Takes 0 args. Method in interface org.omg.PortableInterceptor.ORBInitInfoOperations  Used to add a client-side request Interceptor to the list of   client-side request Interceptors. |
|`add_ior_interceptor()`|add_ior_interceptor|Takes 0 args. Method in interface org.omg.PortableInterceptor.ORBInitInfoOperations  Used to add an IOR Interceptor to the list of IOR Interceptors. |
|`add_server_request_interceptor()`|add_server_request_interceptor|Takes 0 args. Method in interface org.omg.PortableInterceptor.ORBInitInfoOperations  Used to add a server-side request Interceptor to the list of   server-side request Interceptors. |
|`allocate_slot_id()`|allocate_slot_id|Takes 0 args. Method in interface org.omg.PortableInterceptor.ORBInitInfoOperations  Called to allocate a slot on PortableInterceptor.Current. |
|`arguments()`|arguments|Takes 0 args. Method in interface org.omg.PortableInterceptor.ORBInitInfoOperations  Returns the arguments passed to ORB.init. |
|`adapter_name()`|adapter_name|Takes 0 args. Method in interface org.omg.PortableInterceptor.ObjectReferenceTemplate  |
|`arguments()`|arguments|Takes 0 args. Method in interface org.omg.PortableInterceptor.RequestInfoOperations  Returns an array of Parameter objects, containing the   arguments on the operation being invoked. |
|`adapter_id()`|adapter_id|Takes 0 args. Method in interface org.omg.PortableInterceptor.ServerRequestInfoOperations  Returns the opaque identifier for the object adapter. |
|`adapter_name()`|adapter_name|Takes 0 args. Method in interface org.omg.PortableInterceptor.ServerRequestInfoOperations  Returns the sequence of strings that identifies the object  adapter instance that is handling this request. |
|`add_reply_service_context(${1:ServiceContext}, ${2:boolean})`|add_reply_service_context|Takes 2 args. Method in interface org.omg.PortableInterceptor.ServerRequestInfoOperations  Allows Interceptors to add service contexts to the request. |
|`activate()`|activate|Takes 0 args. Method in interface org.omg.PortableServer.POAManagerOperations  This operation changes the state of the POA manager   to active, causing associated POAs to start processing  requests. |
|`ACTIVE`|ACTIVE|Takes 0 args. Static variable in class org.omg.PortableServer.POAManagerPackage.State  |
|`activate_object()`|activate_object|Takes 0 args. Method in interface org.omg.PortableServer.POAOperations  This operation generates an Object Id and enters   the Object Id and the specified servant in the   Active Object Map. |
|`activate_object_with_id(${1:byte[]}, ${2:Servant})`|activate_object_with_id|Takes 2 args. Method in interface org.omg.PortableServer.POAOperations  This operation enters an association between the   specified Object Id and the specified servant in the   Active Object Map. |
|`appendData()`|appendData|Takes 0 args. Method in interface org.w3c.dom.CharacterData  Append the string to the end of the character data of the node. |
|`adoptNode()`|adoptNode|Takes 0 args. Method in interface org.w3c.dom.Document  Attempts to adopt a node from another document to this document. |
|`ATTRIBUTE_NODE`|ATTRIBUTE_NODE|Takes 0 args. Static variable in interface org.w3c.dom.Node  The node is an Attr. |
|`appendChild()`|appendChild|Takes 0 args. Method in interface org.w3c.dom.Node  Adds the node newChild to the end of the list of children  of this node. |
|`addSource()`|addSource|Takes 0 args. Method in class org.w3c.dom.bootstrap.DOMImplementationRegistry  Register an implementation. |
|`AT_TARGET`|AT_TARGET|Takes 0 args. Static variable in interface org.w3c.dom.events.Event  The event is currently being evaluated at the target  EventTarget. |
|`addEventListener(${1:String}, ${2:EventListener}, ${3:boolean})`|addEventListener|Takes 3 args. Method in interface org.w3c.dom.events.EventTarget  This method allows the registration of event listeners on the event  target. |
|`ADDITION`|ADDITION|Takes 0 args. Static variable in interface org.w3c.dom.events.MutationEvent  The Attr was just added. |
|`ACTION_APPEND_AS_CHILDREN`|ACTION_APPEND_AS_CHILDREN|Takes 0 args. Static variable in interface org.w3c.dom.ls.LSParser  Append the result of the parse operation as children of the context  node. |
|`ACTION_INSERT_AFTER`|ACTION_INSERT_AFTER|Takes 0 args. Static variable in interface org.w3c.dom.ls.LSParser  Insert the result of the parse operation as the immediately following  sibling of the context node. |
|`ACTION_INSERT_BEFORE`|ACTION_INSERT_BEFORE|Takes 0 args. Static variable in interface org.w3c.dom.ls.LSParser  Insert the result of the parse operation as the immediately preceding  sibling of the context node. |
|`ACTION_REPLACE`|ACTION_REPLACE|Takes 0 args. Static variable in interface org.w3c.dom.ls.LSParser  Replace the context node with the result of the parse operation. |
|`ACTION_REPLACE_CHILDREN`|ACTION_REPLACE_CHILDREN|Takes 0 args. Static variable in interface org.w3c.dom.ls.LSParser  Replace all the children of the context node with the result of the  parse operation. |
|`abort()`|abort|Takes 0 args. Method in interface org.w3c.dom.ls.LSParser  Abort the loading of the document that is currently being loaded by  the LSParser. |
|`acceptNode()`|acceptNode|Takes 0 args. Method in interface org.w3c.dom.ls.LSParserFilter  This method will be called by the parser at the completion of the  parsing of each node. |
|`addAttribute(${1:String}, ${2:String}, ${3:String}, ${4:String}, ${5:String})`|addAttribute|Takes 5 args. Method in class org.xml.sax.ext.Attributes2Impl  Add an attribute to the end of the list, setting its  "specified" flag to true. |
|`attributeDecl(${1:String}, ${2:String}, ${3:String}, ${4:String}, ${5:String})`|attributeDecl|Takes 5 args. Method in interface org.xml.sax.ext.DeclHandler  Report an attribute type declaration. |
|`attributeDecl(${1:String}, ${2:String}, ${3:String}, ${4:String}, ${5:String})`|attributeDecl|Takes 5 args. Method in class org.xml.sax.ext.DefaultHandler2  |
|`addAttribute(${1:String}, ${2:String}, ${3:String}, ${4:String}, ${5:String})`|addAttribute|Takes 5 args. Method in class org.xml.sax.helpers.AttributesImpl  Add an attribute to the end of the list. |
|`BEFORE_FIRST_LINE`|BEFORE_FIRST_LINE|Takes 0 args. Static variable in class java.awt.BorderLayout  Synonym for PAGE_START. |
|`BEFORE_LINE_BEGINS`|BEFORE_LINE_BEGINS|Takes 0 args. Static variable in class java.awt.BorderLayout  Synonym for LINE_START. |
|`BACKGROUND`|BACKGROUND|Takes 0 args. Static variable in class java.awt.BufferCapabilities.FlipContents  When flip contents are BACKGROUND, the  contents of the back buffer are cleared with the background color after  flipping. |
|`BLACK`|BLACK|Takes 0 args. Static variable in class java.awt.Color  The color black. |
|`BLUE`|BLUE|Takes 0 args. Static variable in class java.awt.Color  The color blue. |
|`black`|black|Takes 0 args. Static variable in class java.awt.Color  The color black. |
|`blue`|blue|Takes 0 args. Static variable in class java.awt.Color  The color blue. |
|`brighter()`|brighter|Takes 0 args. Method in class java.awt.Color  Creates a new Color that is a brighter version of this  Color. |
|`backBuffers`|backBuffers|Takes 0 args. Variable in class java.awt.Component.BltBufferStrategy  The back buffers |
|`BOTTOM_ALIGNMENT`|BOTTOM_ALIGNMENT|Takes 0 args. Static variable in class java.awt.Component  Ease-of-use constant for getAlignmentY. |
|`browse()`|browse|Takes 0 args. Method in class java.awt.Desktop  Launches the default browser to display a URI. |
|`BIT_DEPTH_MULTI`|BIT_DEPTH_MULTI|Takes 0 args. Static variable in class java.awt.DisplayMode  Value of the bit depth if multiple bit depths are supported in this  display mode. |
|`BACK_SPACE`|BACK_SPACE|Takes 0 args. Static variable in class java.awt.Event  The BackSpace key. |
|`BOLD`|BOLD|Takes 0 args. Static variable in class java.awt.Font  The bold style constant. |
|`bytesWidth(${1:byte[]}, ${2:int}, ${3:int})`|bytesWidth|Takes 3 args. Method in class java.awt.FontMetrics  Returns the total advance width for showing the specified array  of bytes in this Font. |
|`BASELINE`|BASELINE|Takes 0 args. Static variable in class java.awt.GridBagConstraints  Possible value for the anchor field. |
|`BASELINE_LEADING`|BASELINE_LEADING|Takes 0 args. Static variable in class java.awt.GridBagConstraints  Possible value for the anchor field. |
|`BASELINE_TRAILING`|BASELINE_TRAILING|Takes 0 args. Static variable in class java.awt.GridBagConstraints  Possible value for the anchor field. |
|`BELOW_BASELINE`|BELOW_BASELINE|Takes 0 args. Static variable in class java.awt.GridBagConstraints  Possible value for the anchor field. |
|`BELOW_BASELINE_LEADING`|BELOW_BASELINE_LEADING|Takes 0 args. Static variable in class java.awt.GridBagConstraints  Possible value for the anchor field. |
|`BELOW_BASELINE_TRAILING`|BELOW_BASELINE_TRAILING|Takes 0 args. Static variable in class java.awt.GridBagConstraints  Possible value for the anchor field. |
|`BOTH`|BOTH|Takes 0 args. Static variable in class java.awt.GridBagConstraints  Resize the component both horizontally and vertically. |
|`bottom`|bottom|Takes 0 args. Variable in class java.awt.Insets  The inset from the bottom. |
|`BACKWARD_TRAVERSAL_KEYS`|BACKWARD_TRAVERSAL_KEYS|Takes 0 args. Static variable in class java.awt.KeyboardFocusManager  The identifier for the Backward focus traversal keys. |
|`B0`|B0|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_B0. |
|`B1`|B1|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_B1. |
|`B10`|B10|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_B10. |
|`B2`|B2|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_B2. |
|`B3`|B3|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_B3. |
|`B4`|B4|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_B4. |
|`B5`|B5|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_B5. |
|`B6`|B6|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_B6. |
|`B7`|B7|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_B7. |
|`B8`|B8|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_B8. |
|`B9`|B9|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_B9. |
|`bounds`|bounds|Takes 0 args. Variable in class java.awt.Polygon  The bounds of this Polygon. |
|`beep()`|beep|Takes 0 args. Method in class java.awt.Toolkit  Emits an audio beep. |
|`BITMASK`|BITMASK|Takes 0 args. Static variable in interface java.awt.Transparency  Represents image data that is guaranteed to be either completely  opaque, with an alpha value of 1.0, or completely transparent,  with an alpha value of 0.0. |
|`BLUECOMPONENT`|BLUECOMPONENT|Takes 0 args. Static variable in class java.awt.color.ICC_ProfileRGB  Used to get a gamma value or TRC for the blue component. |
|`BLOCK_DECREMENT`|BLOCK_DECREMENT|Takes 0 args. Static variable in class java.awt.event.AdjustmentEvent  The block decrement adjustment type. |
|`BLOCK_INCREMENT`|BLOCK_INCREMENT|Takes 0 args. Static variable in class java.awt.event.AdjustmentEvent  The block increment adjustment type. |
|`BUTTON1_DOWN_MASK`|BUTTON1_DOWN_MASK|Takes 0 args. Static variable in class java.awt.event.InputEvent  The Mouse Button1 extended modifier constant. |
|`BUTTON1_MASK`|BUTTON1_MASK|Takes 0 args. Static variable in class java.awt.event.InputEvent  The Mouse Button1 modifier constant. |
|`BUTTON2_DOWN_MASK`|BUTTON2_DOWN_MASK|Takes 0 args. Static variable in class java.awt.event.InputEvent  The Mouse Button2 extended modifier constant. |
|`BUTTON2_MASK`|BUTTON2_MASK|Takes 0 args. Static variable in class java.awt.event.InputEvent  The Mouse Button2 modifier constant. |
|`BUTTON3_DOWN_MASK`|BUTTON3_DOWN_MASK|Takes 0 args. Static variable in class java.awt.event.InputEvent  The Mouse Button3 extended modifier constant. |
|`BUTTON3_MASK`|BUTTON3_MASK|Takes 0 args. Static variable in class java.awt.event.InputEvent  The Mouse Button3 modifier constant. |
|`BUTTON1`|BUTTON1|Takes 0 args. Static variable in class java.awt.event.MouseEvent  Indicates mouse button #1; used by MouseEvent.getButton(). |
|`BUTTON2`|BUTTON2|Takes 0 args. Static variable in class java.awt.event.MouseEvent  Indicates mouse button #2; used by MouseEvent.getButton(). |
|`BUTTON3`|BUTTON3|Takes 0 args. Static variable in class java.awt.event.MouseEvent  Indicates mouse button #3; used by MouseEvent.getButton(). |
|`BOTTOM_ALIGNMENT`|BOTTOM_ALIGNMENT|Takes 0 args. Static variable in class java.awt.font.GraphicAttribute  Aligns bottom of graphic to bottom of line. |
|`BENGALI`|BENGALI|Takes 0 args. Static variable in class java.awt.font.NumericShaper  Identifies the BENGALI range and decimal base. |
|`BACKGROUND`|BACKGROUND|Takes 0 args. Static variable in class java.awt.font.TextAttribute  Attribute key for the paint used to render the background of  the text. |
|`BIDI_EMBEDDING`|BIDI_EMBEDDING|Takes 0 args. Static variable in class java.awt.font.TextAttribute  Attribute key for the embedding level of the text. |
|`beforeOffset()`|beforeOffset|Takes 0 args. Static method in class java.awt.font.TextHitInfo  Creates a TextHitInfo at the specified offset,  associated with the character before the offset. |
|`bandOffsets`|bandOffsets|Takes 0 args. Variable in class java.awt.image.ComponentSampleModel  Offsets for all bands in data array elements. |
|`bankIndices`|bankIndices|Takes 0 args. Variable in class java.awt.image.ComponentSampleModel  Index for each bank storing a band of image data. |
|`banks`|banks|Takes 0 args. Variable in class java.awt.image.DataBuffer  The number of banks in this DataBuffer. |
|`beanContext`|beanContext|Takes 0 args. Variable in class java.beans.beancontext.BeanContextChildSupport  |
|`beanContextChildPeer`|beanContextChildPeer|Takes 0 args. Variable in class java.beans.beancontext.BeanContextChildSupport  The BeanContext in which  this BeanContextChild is nested. |
|`bcsListeners`|bcsListeners|Takes 0 args. Variable in class java.beans.beancontext.BeanContextServicesSupport  List of BeanContextServicesListener objects. |
|`bcsPreDeserializationHook()`|bcsPreDeserializationHook|Takes 0 args. Method in class java.beans.beancontext.BeanContextServicesSupport  called from BeanContextSupport readObject before it deserializes the  children ... |
|`bcsPreSerializationHook()`|bcsPreSerializationHook|Takes 0 args. Method in class java.beans.beancontext.BeanContextServicesSupport  called from BeanContextSupport writeObject before it serializes the  children ... |
|`bcmListeners`|bcmListeners|Takes 0 args. Variable in class java.beans.beancontext.BeanContextSupport  all accesses to the  protected ArrayList bcmListeners  field  shall be synchronized on that object. |
|`bcsChildren()`|bcsChildren|Takes 0 args. Method in class java.beans.beancontext.BeanContextSupport  Returns an iterator of all children  of this BeanContext. |
|`bcsPreDeserializationHook()`|bcsPreDeserializationHook|Takes 0 args. Method in class java.beans.beancontext.BeanContextSupport  called by readObject after defaultReadObject() but prior to  deserialization of any children. |
|`bcsPreSerializationHook()`|bcsPreSerializationHook|Takes 0 args. Method in class java.beans.beancontext.BeanContextSupport  called by writeObject after defaultWriteObject() but prior to  serialization of currently serializable children. |
|`buf`|buf|Takes 0 args. Variable in class java.io.BufferedInputStream  The internal buffer array where the data is stored. |
|`buf`|buf|Takes 0 args. Variable in class java.io.BufferedOutputStream  The internal buffer where data is stored. |
|`buf`|buf|Takes 0 args. Variable in class java.io.ByteArrayInputStream  An array of bytes that was provided  by the creator of the stream. |
|`buf`|buf|Takes 0 args. Variable in class java.io.ByteArrayOutputStream  The buffer where data is stored. |
|`buf`|buf|Takes 0 args. Variable in class java.io.CharArrayReader  The character buffer. |
|`buf`|buf|Takes 0 args. Variable in class java.io.CharArrayWriter  The buffer where data is stored. |
|`bytesTransferred`|bytesTransferred|Takes 0 args. Variable in exception java.io.InterruptedIOException  Reports how many bytes had been transferred as part of the I/O  operation before it was interrupted. |
|`baseWireHandle`|baseWireHandle|Takes 0 args. Static variable in interface java.io.ObjectStreamConstants  First wire handle to be assigned. |
|`buffer`|buffer|Takes 0 args. Variable in class java.io.PipedInputStream  The circular buffer into which incoming data is placed. |
|`buf`|buf|Takes 0 args. Variable in class java.io.PushbackInputStream  The pushback buffer. |
|`booleanValue()`|booleanValue|Takes 0 args. Method in class java.lang.Boolean  Returns the value of this Boolean object as a boolean  primitive. |
|`byteValue()`|byteValue|Takes 0 args. Method in class java.lang.Byte  Returns the value of this Byte as a  byte. |
|`BALINESE`|BALINESE|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Balinese" Unicode character block. |
|`BAMUM`|BAMUM|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Bamum" Unicode character block. |
|`BAMUM_SUPPLEMENT`|BAMUM_SUPPLEMENT|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Bamum Supplement" Unicode character block. |
|`BASIC_LATIN`|BASIC_LATIN|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Basic Latin" Unicode character block. |
|`BATAK`|BATAK|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Batak" Unicode character block. |
|`BENGALI`|BENGALI|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Bengali" Unicode character block. |
|`BLOCK_ELEMENTS`|BLOCK_ELEMENTS|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Block Elements" Unicode character block. |
|`BOPOMOFO`|BOPOMOFO|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Bopomofo" Unicode character block. |
|`BOPOMOFO_EXTENDED`|BOPOMOFO_EXTENDED|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Bopomofo Extended" Unicode character block. |
|`BOX_DRAWING`|BOX_DRAWING|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Box Drawing" Unicode character block. |
|`BRAHMI`|BRAHMI|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Brahmi" Unicode character block. |
|`BRAILLE_PATTERNS`|BRAILLE_PATTERNS|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Braille Patterns" Unicode character block. |
|`BUGINESE`|BUGINESE|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Buginese" Unicode character block. |
|`BUHID`|BUHID|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Buhid" Unicode character block. |
|`BYZANTINE_MUSICAL_SYMBOLS`|BYZANTINE_MUSICAL_SYMBOLS|Takes 0 args. Static variable in class java.lang.Character.UnicodeBlock  Constant for the "Byzantine Musical Symbols" Unicode character block. |
|`byteValue()`|byteValue|Takes 0 args. Method in class java.lang.Double  Returns the value of this Double as a byte (by  casting to a byte). |
|`byteValue()`|byteValue|Takes 0 args. Method in class java.lang.Float  Returns the value of this Float as a byte (by  casting to a byte). |
|`bitCount()`|bitCount|Takes 0 args. Static method in class java.lang.Integer  Returns the number of one-bits in the two's complement binary  representation of the specified int value. |
|`byteValue()`|byteValue|Takes 0 args. Method in class java.lang.Integer  Returns the value of this Integer as a  byte. |
|`bitCount()`|bitCount|Takes 0 args. Static method in class java.lang.Long  Returns the number of one-bits in the two's complement binary  representation of the specified long value. |
|`byteValue()`|byteValue|Takes 0 args. Method in class java.lang.Long  Returns the value of this Long as a  byte. |
|`byteValue()`|byteValue|Takes 0 args. Method in class java.lang.Number  Returns the value of the specified number as a byte. |
|`byteValue()`|byteValue|Takes 0 args. Method in class java.lang.Short  Returns the value of this Short as a  byte. |
|`bindTo()`|bindTo|Takes 0 args. Method in class java.lang.invoke.MethodHandle  Binds a value x to the first argument of a method handle, without invoking it. |
|`bind(${1:Object}, ${2:String}, ${3:MethodType})`|bind|Takes 3 args. Method in class java.lang.invoke.MethodHandles.Lookup  Produces an early-bound method handle for a non-static method. |
|`byteValueExact()`|byteValueExact|Takes 0 args. Method in class java.math.BigDecimal  Converts this BigDecimal to a byte, checking  for lost information. |
|`bitCount()`|bitCount|Takes 0 args. Method in class java.math.BigInteger  Returns the number of bits in the two's complement representation  of this BigInteger that differ from its sign bit. |
|`bitLength()`|bitLength|Takes 0 args. Method in class java.math.BigInteger  Returns the number of bits in the minimal two's-complement  representation of this BigInteger, excluding a sign bit. |
|`bind()`|bind|Takes 0 args. Method in class java.net.DatagramSocket  Binds this DatagramSocket to a specific address & port. |
|`bind(${1:int}, ${2:InetAddress})`|bind|Takes 2 args. Method in class java.net.DatagramSocketImpl  Binds a datagram socket to a local port and address. |
|`bind(${1:SocketAddress}, ${2:int})`|bind|Takes 2 args. Method in class java.net.ServerSocket  Binds the ServerSocket to a specific address  (IP address and port number). |
|`bind()`|bind|Takes 0 args. Method in class java.net.Socket  Binds the socket to a local address. |
|`bind(${1:InetAddress}, ${2:int})`|bind|Takes 2 args. Method in class java.net.SocketImpl  Binds this socket to the specified local IP address and port number. |
|`BIG_ENDIAN`|BIG_ENDIAN|Takes 0 args. Static variable in class java.nio.ByteOrder  Constant denoting big-endian byte order. |
|`bind(${1:SocketAddress}, ${2:int})`|bind|Takes 2 args. Method in class java.nio.channels.AsynchronousServerSocketChannel  Binds the channel's socket to a local address and configures the socket to  listen for connections. |
|`bind()`|bind|Takes 0 args. Method in class java.nio.channels.AsynchronousSocketChannel  |
|`bind()`|bind|Takes 0 args. Method in class java.nio.channels.DatagramChannel  |
|`block()`|block|Takes 0 args. Method in class java.nio.channels.MembershipKey  Block multicast datagrams from the given source address. |
|`bind()`|bind|Takes 0 args. Method in interface java.nio.channels.NetworkChannel  Binds the channel's socket to a local address. |
|`blockingLock()`|blockingLock|Takes 0 args. Method in class java.nio.channels.SelectableChannel  Retrieves the object upon which the configureBlocking and register methods synchronize. |
|`bind(${1:SocketAddress}, ${2:int})`|bind|Takes 2 args. Method in class java.nio.channels.ServerSocketChannel  Binds the channel's socket to a local address and configures the socket to  listen for connections. |
|`bind()`|bind|Takes 0 args. Method in class java.nio.channels.SocketChannel  |
|`begin()`|begin|Takes 0 args. Method in class java.nio.channels.spi.AbstractInterruptibleChannel  Marks the beginning of an I/O operation that might block indefinitely. |
|`blockingLock()`|blockingLock|Takes 0 args. Method in class java.nio.channels.spi.AbstractSelectableChannel  |
|`begin()`|begin|Takes 0 args. Method in class java.nio.channels.spi.AbstractSelector  Marks the beginning of an I/O operation that might block indefinitely. |
|`build()`|build|Takes 0 args. Method in class java.nio.file.attribute.AclEntry.Builder  Constructs an AclEntry from the components of this builder. |
|`bind(${1:String}, ${2:Remote})`|bind|Takes 2 args. Static method in class java.rmi.Naming  Binds the specified name to a remote object. |
|`bind(${1:String}, ${2:Remote})`|bind|Takes 2 args. Method in interface java.rmi.registry.Registry  Binds a remote reference to the specified name in  this registry. |
|`build()`|build|Takes 0 args. Method in class java.security.cert.CertPathBuilder  Attempts to build a certification path using the specified algorithm  parameter set. |
|`bestRowNotPseudo`|bestRowNotPseudo|Takes 0 args. Static variable in interface java.sql.DatabaseMetaData  Indicates that the best row identifier is NOT a pseudo column. |
|`bestRowPseudo`|bestRowPseudo|Takes 0 args. Static variable in interface java.sql.DatabaseMetaData  Indicates that the best row identifier is a pseudo column. |
|`bestRowSession`|bestRowSession|Takes 0 args. Static variable in interface java.sql.DatabaseMetaData  Indicates that the scope of the best row identifier is  the remainder of the current session. |
|`bestRowTemporary`|bestRowTemporary|Takes 0 args. Static variable in interface java.sql.DatabaseMetaData  Indicates that the scope of the best row identifier is  very temporary, lasting only while the  row is being used. |
|`bestRowTransaction`|bestRowTransaction|Takes 0 args. Static variable in interface java.sql.DatabaseMetaData  Indicates that the scope of the best row identifier is  the remainder of the current transaction. |
|`bestRowUnknown`|bestRowUnknown|Takes 0 args. Static variable in interface java.sql.DatabaseMetaData  Indicates that the best row identifier may or may not be a pseudo column. |
|`beforeFirst()`|beforeFirst|Takes 0 args. Method in interface java.sql.ResultSet  Moves the cursor to the front of  this ResultSet object, just before the  first row. |
|`before()`|before|Takes 0 args. Method in class java.sql.Timestamp  Indicates whether this Timestamp object is  earlier than the given Timestamp object. |
|`BIGINT`|BIGINT|Takes 0 args. Static variable in class java.sql.Types  The constant in the Java programming language, sometimes referred  to as a type code, that identifies the generic SQL type  BIGINT. |
|`BINARY`|BINARY|Takes 0 args. Static variable in class java.sql.Types  The constant in the Java programming language, sometimes referred  to as a type code, that identifies the generic SQL type  BINARY. |
|`BIT`|BIT|Takes 0 args. Static variable in class java.sql.Types  The constant in the Java programming language, sometimes referred  to as a type code, that identifies the generic SQL type  BIT. |
|`BLOB`|BLOB|Takes 0 args. Static variable in class java.sql.Types  The constant in the Java programming language, sometimes referred to  as a type code, that identifies the generic SQL type  BLOB. |
|`BOOLEAN`|BOOLEAN|Takes 0 args. Static variable in class java.sql.Types  The constant in the Java programming language, somtimes referred to  as a type code, that identifies the generic SQL type BOOLEAN. |
|`baseIsLeftToRight()`|baseIsLeftToRight|Takes 0 args. Method in class java.text.Bidi  Return true if the base direction is left-to-right. |
|`binarySearch(${1:short[]}, ${2:short})`|binarySearch|Takes 2 args. Static method in class java.util.Arrays  Searches the specified array of shorts for the specified value using  the binary search algorithm. |
|`before()`|before|Takes 0 args. Method in class java.util.Calendar  Returns whether this Calendar represents a time  before the time represented by the specified  Object. |
|`binarySearch(${1:List}, ${2:T}, ${3:Comparator})`|binarySearch|Takes 3 args. Static method in class java.util.Collections  Searches the specified list for the specified object using the binary  search algorithm. |
|`before()`|before|Takes 0 args. Method in class java.util.Date  Tests if this date is before the specified date. |
|`BC`|BC|Takes 0 args. Static variable in class java.util.GregorianCalendar  Value of the ERA field indicating  the period before the common era (before Christ), also known as BCE. |
|`build()`|build|Takes 0 args. Method in class java.util.Locale.Builder  Returns an instance of Locale created from the fields set  on this builder. |
|`block()`|block|Takes 0 args. Method in interface java.util.concurrent.ForkJoinPool.ManagedBlocker  Possibly blocks the current thread, for example waiting for  a lock or condition. |
|`bulkRegister()`|bulkRegister|Takes 0 args. Method in class java.util.concurrent.Phaser  Adds the given number of new unarrived parties to this phaser. |
|`beforeExecute(${1:Thread}, ${2:Runnable})`|beforeExecute|Takes 2 args. Method in class java.util.concurrent.ThreadPoolExecutor  Method invoked prior to executing the given Runnable in the  given thread. |
|`BEST_COMPRESSION`|BEST_COMPRESSION|Takes 0 args. Static variable in class java.util.zip.Deflater  Compression level for best compression. |
|`BEST_SPEED`|BEST_SPEED|Takes 0 args. Static variable in class java.util.zip.Deflater  Compression level for fastest compression. |
|`buf`|buf|Takes 0 args. Variable in class java.util.zip.DeflaterInputStream  Input buffer for reading compressed data. |
|`buf`|buf|Takes 0 args. Variable in class java.util.zip.DeflaterOutputStream  Output buffer for writing compressed data. |
|`buf`|buf|Takes 0 args. Variable in class java.util.zip.InflaterInputStream  Input buffer for decompression. |
|`buf`|buf|Takes 0 args. Variable in class java.util.zip.InflaterOutputStream  Output buffer for writing uncompressed data. |
|`BUSY`|BUSY|Takes 0 args. Static variable in class javax.accessibility.AccessibleState  Indicates the current object is busy. |
|`bitOffset`|bitOffset|Takes 0 args. Variable in class javax.imageio.stream.ImageInputStreamImpl  The current bit offset within the stream. |
|`byteOrder`|byteOrder|Takes 0 args. Variable in class javax.imageio.stream.ImageInputStreamImpl  The byte order of the stream as an instance of the enumeration  class java.nio.ByteOrder, where  ByteOrder.BIG_ENDIAN indicates network byte order  and ByteOrder.LITTLE_ENDIAN indicates the reverse  order. |
|`boxedClass()`|boxedClass|Takes 0 args. Method in interface javax.lang.model.util.Types  Returns the class of a boxed value of a given primitive type. |
|`between(${1:ValueExp}, ${2:ValueExp}, ${3:ValueExp})`|between|Takes 3 args. Static method in class javax.management.Query  Returns a query expression that represents the constraint that one  value is between two other values. |
|`BIGDECIMAL`|BIGDECIMAL|Takes 0 args. Static variable in class javax.management.openmbean.SimpleType  The SimpleType instance describing values whose  Java class name is java.math.BigDecimal. |
|`BIGINTEGER`|BIGINTEGER|Takes 0 args. Static variable in class javax.management.openmbean.SimpleType  The SimpleType instance describing values whose  Java class name is java.math.BigInteger. |
|`BOOLEAN`|BOOLEAN|Takes 0 args. Static variable in class javax.management.openmbean.SimpleType  The SimpleType instance describing values whose  Java class name is java.lang.Boolean. |
|`BYTE`|BYTE|Takes 0 args. Static variable in class javax.management.openmbean.SimpleType  The SimpleType instance describing values whose  Java class name is java.lang.Byte. |
|`BATCHSIZE`|BATCHSIZE|Takes 0 args. Static variable in interface javax.naming.Context  Constant that holds the name of the environment property for  specifying the batch size to use when returning data via the  service's protocol. |
|`bind(${1:Name}, ${2:Object})`|bind|Takes 2 args. Method in interface javax.naming.Context  Binds a name to an object. |
|`bind(${1:Name}, ${2:Object})`|bind|Takes 2 args. Method in class javax.naming.InitialContext  |
|`bind(${1:Name}, ${2:Object}, ${3:Attributes})`|bind|Takes 3 args. Method in interface javax.naming.directory.DirContext  Binds a name to an object, along with associated attributes. |
|`bind(${1:Name}, ${2:Object}, ${3:Attributes})`|bind|Takes 3 args. Method in class javax.naming.directory.InitialDirContext  |
|`beginHandshake()`|beginHandshake|Takes 0 args. Method in class javax.net.ssl.SSLEngine  Initiates handshaking (initial or renegotiation) on this SSLEngine. |
|`bytesConsumed()`|bytesConsumed|Takes 0 args. Method in class javax.net.ssl.SSLEngineResult  Returns the number of bytes consumed from the input buffer. |
|`bytesProduced()`|bytesProduced|Takes 0 args. Method in class javax.net.ssl.SSLEngineResult  Returns the number of bytes written to the output buffer. |
|`BIND`|BIND|Takes 0 args. Static variable in class javax.print.attribute.standard.Finishings  This value indicates that a binding is to be applied to the document;  the type and placement of the binding is site-defined. |
|`B0`|B0|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.ISO  Specifies the ISO B0 size, 1000 mm by 1414 mm. |
|`B1`|B1|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.ISO  Specifies the ISO B1 size, 707 mm by 1000 mm. |
|`B10`|B10|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.ISO  Specifies the ISO B10 size, 31 mm by 44 mm. |
|`B2`|B2|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.ISO  Specifies the ISO B2 size, 500 mm by 707 mm. |
|`B3`|B3|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.ISO  Specifies the ISO B3 size, 353 mm by 500 mm. |
|`B4`|B4|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.ISO  Specifies the ISO B4 size, 250 mm by 353 mm. |
|`B5`|B5|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.ISO  Specifies the ISO B5 size, 176 mm by 250 mm. |
|`B6`|B6|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.ISO  Specifies the ISO B6 size, 125 mm by 176 mm. |
|`B7`|B7|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.ISO  Specifies the ISO B7 size, 88 mm by 125 mm. |
|`B8`|B8|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.ISO  Specifies the ISO B8 size, 62 mm by 88 mm. |
|`B9`|B9|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.ISO  Specifies the ISO B9 size, 44 mm by 62 mm. |
|`B0`|B0|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.JIS  Specifies the JIS B0 size, 1030 mm by 1456 mm. |
|`B1`|B1|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.JIS  Specifies the JIS B1 size, 728 mm by 1030 mm. |
|`B10`|B10|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.JIS  Specifies the JIS B10 size, 32 mm by 45 mm. |
|`B2`|B2|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.JIS  Specifies the JIS B2 size, 515 mm by 728 mm. |
|`B3`|B3|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.JIS  Specifies the JIS B3 size, 364 mm by 515 mm. |
|`B4`|B4|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.JIS  Specifies the JIS B4 size, 257 mm by 364 mm. |
|`B5`|B5|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.JIS  Specifies the JIS B5 size, 182 mm by 257 mm. |
|`B6`|B6|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.JIS  Specifies the JIS B6 size, 128 mm by 182 mm. |
|`B7`|B7|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.JIS  Specifies the JIS B7 size, 91 mm by 128 mm. |
|`B8`|B8|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.JIS  Specifies the JIS B8 size, 64 mm by 91 mm. |
|`B9`|B9|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaSize.JIS  Specifies the JIS B9 size, 45 mm by 64 mm. |
|`BOTTOM`|BOTTOM|Takes 0 args. Static variable in class javax.print.attribute.standard.MediaTray  The bottom input tray in the printer. |
|`byteLength`|byteLength|Takes 0 args. Variable in class javax.sound.midi.MidiFileFormat  The length of the MIDI file in bytes. |
|`bank`|bank|Takes 0 args. Variable in class javax.sound.midi.VoiceStatus  The bank number of the instrument that this voice is currently using. |
|`bigEndian`|bigEndian|Takes 0 args. Variable in class javax.sound.sampled.AudioFormat  Indicates whether the audio data is stored in big-endian or little-endian order. |
|`BALANCE`|BALANCE|Takes 0 args. Static variable in class javax.sound.sampled.FloatControl.Type  Represents a control for the relative balance of a stereo signal  between two stereo speakers. |
|`BINARY_STREAM_PARAM`|BINARY_STREAM_PARAM|Takes 0 args. Static variable in class javax.sql.rowset.BaseRowSet  A constant indicating to a RowSetReaderImpl object  that a given parameter is a binary stream. |
|`binaryStream`|binaryStream|Takes 0 args. Variable in class javax.sql.rowset.BaseRowSet  The InputStream object that will be  returned by the method getBinaryStream, which is  specified in the ResultSet interface. |
|`BORDER_PAINTED_CHANGED_PROPERTY`|BORDER_PAINTED_CHANGED_PROPERTY|Takes 0 args. Static variable in class javax.swing.AbstractButton  Identifies a change to having the border drawn,  or having it not drawn. |
|`buttons`|buttons|Takes 0 args. Variable in class javax.swing.ButtonGroup  |
|`BUFFERED_OPTION`|BUFFERED_OPTION|Takes 0 args. Static variable in class javax.swing.DebugGraphics  Show buffered operations in a separate Frame. |
|`beginDraggingFrame()`|beginDraggingFrame|Takes 0 args. Method in class javax.swing.DefaultDesktopManager  |
|`beginResizingFrame(${1:JComponent}, ${2:int})`|beginResizingFrame|Takes 2 args. Method in class javax.swing.DefaultDesktopManager  |
|`beginDraggingFrame()`|beginDraggingFrame|Takes 0 args. Method in interface javax.swing.DesktopManager  This method is normally called when the user has indicated that  they will begin dragging a component around. |
|`beginResizingFrame(${1:JComponent}, ${2:int})`|beginResizingFrame|Takes 2 args. Method in interface javax.swing.DesktopManager  This methods is normally called when the user has indicated that  they will begin resizing the frame. |
|`BORDER_PAINTED_FLAT_CHANGED_PROPERTY`|BORDER_PAINTED_FLAT_CHANGED_PROPERTY|Takes 0 args. Static variable in class javax.swing.JCheckBox  Identifies a change to the flat property. |
|`blockIncrement`|blockIncrement|Takes 0 args. Variable in class javax.swing.JScrollBar  |
|`BOTTOM`|BOTTOM|Takes 0 args. Static variable in class javax.swing.JSplitPane  Used to add a Component below the other  Component. |
|`BACKINGSTORE_SCROLL_MODE`|BACKINGSTORE_SCROLL_MODE|Takes 0 args. Static variable in class javax.swing.JViewport  Draws viewport contents into an offscreen image. |
|`BLIT_SCROLL_MODE`|BLIT_SCROLL_MODE|Takes 0 args. Static variable in class javax.swing.JViewport  Use graphics.copyArea to implement scrolling. |
|`backingStoreImage`|backingStoreImage|Takes 0 args. Variable in class javax.swing.JViewport  The view image used for a backing store. |
|`BASELINE`|BASELINE|Takes 0 args. Static variable in class javax.swing.SpringLayout  Specifies the baseline of a component. |
|`BOTTOM`|BOTTOM|Takes 0 args. Static variable in interface javax.swing.SwingConstants  Box-orientation constant used to specify the bottom of a box. |
|`bevelType`|bevelType|Takes 0 args. Variable in class javax.swing.border.BevelBorder  |
|`bottom`|bottom|Takes 0 args. Variable in class javax.swing.border.EmptyBorder  |
|`BELOW_BOTTOM`|BELOW_BOTTOM|Takes 0 args. Static variable in class javax.swing.border.TitledBorder  Position the title below the border's bottom line. |
|`BELOW_TOP`|BELOW_TOP|Takes 0 args. Static variable in class javax.swing.border.TitledBorder  Position the title below the border's top line. |
|`BOTTOM`|BOTTOM|Takes 0 args. Static variable in class javax.swing.border.TitledBorder  Position the title in the middle of the border's bottom line. |
|`border`|border|Takes 0 args. Variable in class javax.swing.border.TitledBorder  |
|`buildChooser()`|buildChooser|Takes 0 args. Method in class javax.swing.colorchooser.AbstractColorChooserPanel  Builds a new chooser panel. |
|`borderListener`|borderListener|Takes 0 args. Variable in class javax.swing.plaf.basic.BasicInternalFrameUI  |
|`buttonIndex`|buttonIndex|Takes 0 args. Variable in class javax.swing.plaf.basic.BasicOptionPaneUI.ButtonActionListener  |
|`burstStringInto(${1:Container}, ${2:String}, ${3:int})`|burstStringInto|Takes 3 args. Method in class javax.swing.plaf.basic.BasicOptionPaneUI  Recursively creates new JLabel instances to represent d. |
|`boxRect`|boxRect|Takes 0 args. Variable in class javax.swing.plaf.basic.BasicProgressBarUI  Used to hold the location and size of the bouncing box (returned  by getBox) to be painted. |
|`buttonListener`|buttonListener|Takes 0 args. Variable in class javax.swing.plaf.basic.BasicScrollBarUI  |
|`beginDragDividerLocation`|beginDragDividerLocation|Takes 0 args. Variable in class javax.swing.plaf.basic.BasicSplitPaneUI  Location of the divider when the dragging session began. |
|`borderInsets`|borderInsets|Takes 0 args. Static variable in class javax.swing.plaf.metal.MetalBorders.ButtonBorder  |
|`borderInsets`|borderInsets|Takes 0 args. Static variable in class javax.swing.plaf.metal.MetalBorders.MenuBarBorder  |
|`borderInsets`|borderInsets|Takes 0 args. Static variable in class javax.swing.plaf.metal.MetalBorders.MenuItemBorder  |
|`borderInsets`|borderInsets|Takes 0 args. Static variable in class javax.swing.plaf.metal.MetalBorders.PopupMenuBorder  |
|`bumps`|bumps|Takes 0 args. Variable in class javax.swing.plaf.metal.MetalBorders.ToolBarBorder  |
|`bumps`|bumps|Takes 0 args. Variable in class javax.swing.plaf.metal.MetalScrollBarUI  |
|`BACKGROUND`|BACKGROUND|Takes 0 args. Static variable in class javax.swing.plaf.synth.ColorType  ColorType for the background of a region. |
|`BUTTON`|BUTTON|Takes 0 args. Static variable in class javax.swing.plaf.synth.Region  Button region. |
|`BAD_LOCATION`|BAD_LOCATION|Takes 0 args. Static variable in class javax.swing.text.AbstractDocument  Error message to indicate a bad location. |
|`BidiElementName`|BidiElementName|Takes 0 args. Static variable in class javax.swing.text.AbstractDocument  Name of elements used to hold a unidirectional run |
|`baselineLayout(${1:int}, ${2:int}, ${3:int[]}, ${4:int[]})`|baselineLayout|Takes 4 args. Method in class javax.swing.text.BoxView  Computes the location and extent of each child view  in this BoxView given the targetSpan,  which is the width (or height) of the region we have to  work with. |
|`baselineRequirements(${1:int}, ${2:SizeRequirements})`|baselineRequirements|Takes 2 args. Method in class javax.swing.text.BoxView  Calculates the size requirements for this BoxView  by examining the size of each child view. |
|`backwardAction`|backwardAction|Takes 0 args. Static variable in class javax.swing.text.DefaultEditorKit  Name of the Action for moving the caret  logically backward one position. |
|`beepAction`|beepAction|Takes 0 args. Static variable in class javax.swing.text.DefaultEditorKit  Name of the action to create a beep. |
|`beginAction`|beginAction|Takes 0 args. Static variable in class javax.swing.text.DefaultEditorKit  Name of the Action for moving the caret  to the beginning of the document. |
|`beginLineAction`|beginLineAction|Takes 0 args. Static variable in class javax.swing.text.DefaultEditorKit  Name of the Action for moving the caret  to the beginning of a line. |
|`beginParagraphAction`|beginParagraphAction|Takes 0 args. Static variable in class javax.swing.text.DefaultEditorKit  Name of the Action for moving the caret  to the beginning of a paragraph. |
|`beginWordAction`|beginWordAction|Takes 0 args. Static variable in class javax.swing.text.DefaultEditorKit  Name of the Action for moving the caret  to the beginning of a word. |
|`BUFFER_SIZE_DEFAULT`|BUFFER_SIZE_DEFAULT|Takes 0 args. Static variable in class javax.swing.text.DefaultStyledDocument  The default size of the initial content buffer. |
|`buffer`|buffer|Takes 0 args. Variable in class javax.swing.text.DefaultStyledDocument  |
|`breakView(${1:int}, ${2:int}, ${3:float}, ${4:float})`|breakView|Takes 4 args. Method in class javax.swing.text.GlyphView  Breaks this view on the given axis at the given length. |
|`breakView(${1:int}, ${2:float}, ${3:Shape})`|breakView|Takes 3 args. Method in class javax.swing.text.ParagraphView  Breaks this view on the given axis at the given length. |
|`Backward`|Backward|Takes 0 args. Static variable in class javax.swing.text.Position.Bias  Indicates a bias toward the previous character  in the model. |
|`Background`|Background|Takes 0 args. Static variable in class javax.swing.text.StyleConstants  Name of the background color attribute. |
|`BidiLevel`|BidiLevel|Takes 0 args. Static variable in class javax.swing.text.StyleConstants  Bidirectional level of a character as assigned by the Unicode bidi  algorithm. |
|`Bold`|Bold|Takes 0 args. Static variable in class javax.swing.text.StyleConstants  Name of the bold attribute. |
|`BadBreakWeight`|BadBreakWeight|Takes 0 args. Static variable in class javax.swing.text.View  The weight to indicate a view is a bad break  opportunity for the purpose of formatting. |
|`breakView(${1:int}, ${2:int}, ${3:float}, ${4:float})`|breakView|Takes 4 args. Method in class javax.swing.text.View  Tries to break this view on the given axis. |
|`BACKGROUND`|BACKGROUND|Takes 0 args. Static variable in class javax.swing.text.html.CSS.Attribute  |
|`BACKGROUND_ATTACHMENT`|BACKGROUND_ATTACHMENT|Takes 0 args. Static variable in class javax.swing.text.html.CSS.Attribute  |
|`BACKGROUND_COLOR`|BACKGROUND_COLOR|Takes 0 args. Static variable in class javax.swing.text.html.CSS.Attribute  |
|`BACKGROUND_IMAGE`|BACKGROUND_IMAGE|Takes 0 args. Static variable in class javax.swing.text.html.CSS.Attribute  |
|`BACKGROUND_POSITION`|BACKGROUND_POSITION|Takes 0 args. Static variable in class javax.swing.text.html.CSS.Attribute  |
|`BACKGROUND_REPEAT`|BACKGROUND_REPEAT|Takes 0 args. Static variable in class javax.swing.text.html.CSS.Attribute  |
|`BORDER`|BORDER|Takes 0 args. Static variable in class javax.swing.text.html.CSS.Attribute  |
|`BORDER_BOTTOM`|BORDER_BOTTOM|Takes 0 args. Static variable in class javax.swing.text.html.CSS.Attribute  |
|`BORDER_BOTTOM_COLOR`|BORDER_BOTTOM_COLOR|Takes 0 args. Static variable in class javax.swing.text.html.CSS.Attribute  |
|`BORDER_BOTTOM_STYLE`|BORDER_BOTTOM_STYLE|Takes 0 args. Static variable in class javax.swing.text.html.CSS.Attribute  |
|`BORDER_BOTTOM_WIDTH`|BORDER_BOTTOM_WIDTH|Takes 0 args. Static variable in class javax.swing.text.html.CSS.Attribute  |
|`BORDER_COLOR`|BORDER_COLOR|Takes 0 args. Static variable in class javax.swing.text.html.CSS.Attribute  |
|`BORDER_LEFT`|BORDER_LEFT|Takes 0 args. Static variable in class javax.swing.text.html.CSS.Attribute  |
|`BORDER_LEFT_COLOR`|BORDER_LEFT_COLOR|Takes 0 args. Static variable in class javax.swing.text.html.CSS.Attribute  |
|`BORDER_LEFT_STYLE`|BORDER_LEFT_STYLE|Takes 0 args. Static variable in class javax.swing.text.html.CSS.Attribute  |
|`BORDER_LEFT_WIDTH`|BORDER_LEFT_WIDTH|Takes 0 args. Static variable in class javax.swing.text.html.CSS.Attribute  |
|`BORDER_RIGHT`|BORDER_RIGHT|Takes 0 args. Static variable in class javax.swing.text.html.CSS.Attribute  |
|`BORDER_RIGHT_COLOR`|BORDER_RIGHT_COLOR|Takes 0 args. Static variable in class javax.swing.text.html.CSS.Attribute  |
|`BORDER_RIGHT_STYLE`|BORDER_RIGHT_STYLE|Takes 0 args. Static variable in class javax.swing.text.html.CSS.Attribute  |
|`BORDER_RIGHT_WIDTH`|BORDER_RIGHT_WIDTH|Takes 0 args. Static variable in class javax.swing.text.html.CSS.Attribute  |
|`BORDER_STYLE`|BORDER_STYLE|Takes 0 args. Static variable in class javax.swing.text.html.CSS.Attribute  |
|`BORDER_TOP`|BORDER_TOP|Takes 0 args. Static variable in class javax.swing.text.html.CSS.Attribute  |
|`BORDER_TOP_COLOR`|BORDER_TOP_COLOR|Takes 0 args. Static variable in class javax.swing.text.html.CSS.Attribute  |
|`BORDER_TOP_STYLE`|BORDER_TOP_STYLE|Takes 0 args. Static variable in class javax.swing.text.html.CSS.Attribute  |
|`BORDER_TOP_WIDTH`|BORDER_TOP_WIDTH|Takes 0 args. Static variable in class javax.swing.text.html.CSS.Attribute  |
|`BORDER_WIDTH`|BORDER_WIDTH|Takes 0 args. Static variable in class javax.swing.text.html.CSS.Attribute  |
|`BACKGROUND`|BACKGROUND|Takes 0 args. Static variable in class javax.swing.text.html.HTML.Attribute  |
|`BGCOLOR`|BGCOLOR|Takes 0 args. Static variable in class javax.swing.text.html.HTML.Attribute  |
|`BORDER`|BORDER|Takes 0 args. Static variable in class javax.swing.text.html.HTML.Attribute  |
|`BASE`|BASE|Takes 0 args. Static variable in class javax.swing.text.html.HTML.Tag  |
|`BASEFONT`|BASEFONT|Takes 0 args. Static variable in class javax.swing.text.html.HTML.Tag  |
|`BIG`|BIG|Takes 0 args. Static variable in class javax.swing.text.html.HTML.Tag  |
|`BLOCKQUOTE`|BLOCKQUOTE|Takes 0 args. Static variable in class javax.swing.text.html.HTML.Tag  |
|`BODY`|BODY|Takes 0 args. Static variable in class javax.swing.text.html.HTML.Tag  |
|`BR`|BR|Takes 0 args. Static variable in class javax.swing.text.html.HTML.Tag  |
|`breaksFlow()`|breaksFlow|Takes 0 args. Method in class javax.swing.text.html.HTML.Tag  Returns true if this tag causes a  line break to the flow of data, otherwise returns  false. |
|`blockClose()`|blockClose|Takes 0 args. Method in class javax.swing.text.html.HTMLDocument.HTMLReader  Adds an instruction to the parse buffer to close out  a block element of the given type. |
|`blockOpen(${1:HTML.Tag}, ${2:MutableAttributeSet})`|blockOpen|Takes 2 args. Method in class javax.swing.text.html.HTMLDocument.HTMLReader  Adds an instruction to the parse buffer to create a  block element with the given attributes. |
|`BOLD_ACTION`|BOLD_ACTION|Takes 0 args. Static variable in class javax.swing.text.html.HTMLEditorKit  The bold action identifier |
|`breakView(${1:int}, ${2:int}, ${3:float}, ${4:float})`|breakView|Takes 4 args. Method in class javax.swing.text.html.InlineView  Tries to break this view on the given axis. |
|`base`|base|Takes 0 args. Variable in class javax.swing.text.html.parser.DTD  |
|`body`|body|Takes 0 args. Variable in class javax.swing.text.html.parser.DTD  |
|`breaksFlow()`|breaksFlow|Takes 0 args. Method in class javax.swing.text.html.parser.TagElement  |
|`breadthFirstEnumeration()`|breadthFirstEnumeration|Takes 0 args. Method in class javax.swing.tree.DefaultMutableTreeNode  Creates and returns an enumeration that traverses the subtree rooted at  this node in breadth-first order. |
|`border`|border|Takes 0 args. Variable in class javax.swing.tree.DefaultTreeCellEditor.DefaultTextField  Border to use. |
|`borderSelectionColor`|borderSelectionColor|Takes 0 args. Variable in class javax.swing.tree.DefaultTreeCellEditor  True if the border selection color should be drawn. |
|`backgroundNonSelectionColor`|backgroundNonSelectionColor|Takes 0 args. Variable in class javax.swing.tree.DefaultTreeCellRenderer  Color to use for the background when the node isn't selected. |
|`backgroundSelectionColor`|backgroundSelectionColor|Takes 0 args. Variable in class javax.swing.tree.DefaultTreeCellRenderer  Color to use for the background when a node is selected. |
|`borderSelectionColor`|borderSelectionColor|Takes 0 args. Variable in class javax.swing.tree.DefaultTreeCellRenderer  Color to use for the focus indicator when the node has focus. |
|`beginUpdate()`|beginUpdate|Takes 0 args. Method in class javax.swing.undo.UndoableEditSupport  |
|`beforeMarshal()`|beforeMarshal|Takes 0 args. Method in class javax.xml.bind.Marshaller.Listener    Callback method invoked before marshalling from source to XML. |
|`beforeUnmarshal(${1:Object}, ${2:Object})`|beforeUnmarshal|Takes 2 args. Method in class javax.xml.bind.Unmarshaller.Listener    Callback method invoked before unmarshalling into target. |
|`BASE64`|BASE64|Takes 0 args. Static variable in interface javax.xml.crypto.dsig.Transform  The Base64  transform algorithm URI. |
|`build()`|build|Takes 0 args. Method in class javax.xml.ws.wsaddressing.W3CEndpointReferenceBuilder  Builds a W3CEndpointReference from the accumulated  properties set on this W3CEndpointReferenceBuilder  instance. |
|`BOOLEAN`|BOOLEAN|Takes 0 args. Static variable in class javax.xml.xpath.XPathConstants  The XPath 1.0 boolean data type. |
|`BAD_BINDINGS`|BAD_BINDINGS|Takes 0 args. Static variable in exception org.ietf.jgss.GSSException  Channel bindings mismatch. |
|`BAD_MECH`|BAD_MECH|Takes 0 args. Static variable in exception org.ietf.jgss.GSSException  Unsupported mechanism requested. |
|`BAD_MIC`|BAD_MIC|Takes 0 args. Static variable in exception org.ietf.jgss.GSSException  Token had invalid integrity check. |
|`BAD_NAME`|BAD_NAME|Takes 0 args. Static variable in exception org.ietf.jgss.GSSException  Invalid name provided. |
|`BAD_NAMETYPE`|BAD_NAMETYPE|Takes 0 args. Static variable in exception org.ietf.jgss.GSSException  Name of unsupported type provided. |
|`BAD_QOP`|BAD_QOP|Takes 0 args. Static variable in exception org.ietf.jgss.GSSException  Unsupported QOP value. |
|`BAD_STATUS`|BAD_STATUS|Takes 0 args. Static variable in exception org.ietf.jgss.GSSException  Invalid status code. |
|`binding_name`|binding_name|Takes 0 args. Variable in class org.omg.CosNaming.Binding  |
|`binding_type`|binding_type|Takes 0 args. Variable in class org.omg.CosNaming.Binding  |
|`bind(${1:NameComponent[]}, ${2:Object})`|bind|Takes 2 args. Method in interface org.omg.CosNaming.NamingContextOperations  Creates a binding of a name and an object in the naming context. |
|`bind_context(${1:NameComponent[]}, ${2:NamingContext})`|bind_context|Takes 2 args. Method in interface org.omg.CosNaming.NamingContextOperations  Names an object that is a naming context. |
|`bind_new_context()`|bind_new_context|Takes 0 args. Method in interface org.omg.CosNaming.NamingContextOperations  This operation creates a new context and binds it to the name  supplied as an argument. |
|`bind(${1:NameComponent[]}, ${2:Object})`|bind|Takes 2 args. Method in class org.omg.CosNaming._NamingContextExtStub  Creates a binding of a name and an object in the naming context. |
|`bind_context(${1:NameComponent[]}, ${2:NamingContext})`|bind_context|Takes 2 args. Method in class org.omg.CosNaming._NamingContextExtStub  Names an object that is a naming context. |
|`bind_new_context()`|bind_new_context|Takes 0 args. Method in class org.omg.CosNaming._NamingContextExtStub  This operation creates a new context and binds it to the name  supplied as an argument. |
|`bind(${1:NameComponent[]}, ${2:Object})`|bind|Takes 2 args. Method in class org.omg.CosNaming._NamingContextStub  Creates a binding of a name and an object in the naming context. |
|`bind_context(${1:NameComponent[]}, ${2:NamingContext})`|bind_context|Takes 2 args. Method in class org.omg.CosNaming._NamingContextStub  Names an object that is a naming context. |
|`bind_new_context()`|bind_new_context|Takes 0 args. Method in class org.omg.CosNaming._NamingContextStub  This operation creates a new context and binds it to the name  supplied as an argument. |
|`BUBBLING_PHASE`|BUBBLING_PHASE|Takes 0 args. Static variable in interface org.w3c.dom.events.Event  The current event phase is the bubbling phase. |
|`COMPONENT_EVENT_MASK`|COMPONENT_EVENT_MASK|Takes 0 args. Static variable in class java.awt.AWTEvent  The event mask for selecting component events. |
|`CONTAINER_EVENT_MASK`|CONTAINER_EVENT_MASK|Takes 0 args. Static variable in class java.awt.AWTEvent  The event mask for selecting container events. |
|`consume()`|consume|Takes 0 args. Method in class java.awt.AWTEvent  Consumes this event, if this event can be consumed. |
|`consumed`|consumed|Takes 0 args. Variable in class java.awt.AWTEvent  Controls whether or not the event is sent back down to the peer once the  source has processed it|
|`caretPositionChanged()`|caretPositionChanged|Takes 0 args. Method in class java.awt.AWTEventMulticaster  Handles the caretPositionChanged event by invoking the  caretPositionChanged methods on listener-a and listener-b. |
|`componentAdded()`|componentAdded|Takes 0 args. Method in class java.awt.AWTEventMulticaster  Handles the componentAdded container event by invoking the  componentAdded methods on listener-a and listener-b. |
|`componentHidden()`|componentHidden|Takes 0 args. Method in class java.awt.AWTEventMulticaster  Handles the componentHidden event by invoking the  componentHidden methods on listener-a and listener-b. |
|`componentMoved()`|componentMoved|Takes 0 args. Method in class java.awt.AWTEventMulticaster  Handles the componentMoved event by invoking the  componentMoved methods on listener-a and listener-b. |
|`componentRemoved()`|componentRemoved|Takes 0 args. Method in class java.awt.AWTEventMulticaster  Handles the componentRemoved container event by invoking the  componentRemoved methods on listener-a and listener-b. |
|`componentResized()`|componentResized|Takes 0 args. Method in class java.awt.AWTEventMulticaster  Handles the componentResized event by invoking the  componentResized methods on listener-a and listener-b. |
|`componentShown()`|componentShown|Takes 0 args. Method in class java.awt.AWTEventMulticaster  Handles the componentShown event by invoking the  componentShown methods on listener-a and listener-b. |
|`CLEAR`|CLEAR|Takes 0 args. Static variable in class java.awt.AlphaComposite  Both the color and the alpha of the destination are cleared  (Porter-Duff Clear rule). |
|`Clear`|Clear|Takes 0 args. Static variable in class java.awt.AlphaComposite  AlphaComposite object that implements the opaque CLEAR rule  with an alpha of 1.0f. |
|`createContext(${1:ColorModel}, ${2:ColorModel}, ${3:RenderingHints})`|createContext|Takes 3 args. Method in class java.awt.AlphaComposite  Creates a context for the compositing operation. |
|`CAP_BUTT`|CAP_BUTT|Takes 0 args. Static variable in class java.awt.BasicStroke  Ends unclosed subpaths and dash segments with no added  decoration. |
|`CAP_ROUND`|CAP_ROUND|Takes 0 args. Static variable in class java.awt.BasicStroke  Ends unclosed subpaths and dash segments with a round  decoration that has a radius equal to half of the width  of the pen. |
|`CAP_SQUARE`|CAP_SQUARE|Takes 0 args. Static variable in class java.awt.BasicStroke  Ends unclosed subpaths and dash segments with a square  projection that extends beyond the end of the segment  to a distance equal to half of the line width. |
|`createStrokedShape()`|createStrokedShape|Takes 0 args. Method in class java.awt.BasicStroke  Returns a Shape whose interior defines the  stroked outline of a specified Shape. |
|`CENTER`|CENTER|Takes 0 args. Static variable in class java.awt.BorderLayout  The center layout constraint (middle of container). |
|`COPIED`|COPIED|Takes 0 args. Static variable in class java.awt.BufferCapabilities.FlipContents  When flip contents are COPIED, the  contents of the back buffer are copied to the front buffer when  flipping. |
|`clone()`|clone|Takes 0 args. Method in class java.awt.BufferCapabilities  |
|`createBufferStrategy(${1:int}, ${2:BufferCapabilities})`|createBufferStrategy|Takes 2 args. Method in class java.awt.Canvas  Creates a new strategy for multi-buffering on this component with the  required buffer capabilities. |
|`CYAN`|CYAN|Takes 0 args. Static variable in class java.awt.Color  The color cyan. |
|`createContext(${1:ColorModel}, ${2:Rectangle}, ${3:Rectangle2D}, ${4:AffineTransform}, ${5:RenderingHints})`|createContext|Takes 5 args. Method in class java.awt.Color  Creates and returns a PaintContext used to  generate a solid color field pattern. |
|`cyan`|cyan|Takes 0 args. Static variable in class java.awt.Color  The color cyan. |
|`componentHidden()`|componentHidden|Takes 0 args. Method in class java.awt.Component.AccessibleAWTComponent.AccessibleAWTComponentHandler  |
|`componentMoved()`|componentMoved|Takes 0 args. Method in class java.awt.Component.AccessibleAWTComponent.AccessibleAWTComponentHandler  |
|`componentResized()`|componentResized|Takes 0 args. Method in class java.awt.Component.AccessibleAWTComponent.AccessibleAWTComponentHandler  |
|`componentShown()`|componentShown|Takes 0 args. Method in class java.awt.Component.AccessibleAWTComponent.AccessibleAWTComponentHandler  |
|`contains()`|contains|Takes 0 args. Method in class java.awt.Component.AccessibleAWTComponent  Checks whether the specified point is within this object's bounds,  where the point's x and y coordinates are defined to be relative to  the coordinate system of the object. |
|`caps`|caps|Takes 0 args. Variable in class java.awt.Component.BltBufferStrategy  The buffering capabilities |
|`contentsLost()`|contentsLost|Takes 0 args. Method in class java.awt.Component.BltBufferStrategy  |
|`contentsRestored()`|contentsRestored|Takes 0 args. Method in class java.awt.Component.BltBufferStrategy  |
|`createBackBuffers()`|createBackBuffers|Takes 0 args. Method in class java.awt.Component.BltBufferStrategy  Creates the back buffers |
|`caps`|caps|Takes 0 args. Variable in class java.awt.Component.FlipBufferStrategy  The buffering capabilities |
|`contentsLost()`|contentsLost|Takes 0 args. Method in class java.awt.Component.FlipBufferStrategy  |
|`contentsRestored()`|contentsRestored|Takes 0 args. Method in class java.awt.Component.FlipBufferStrategy  |
|`createBuffers(${1:int}, ${2:BufferCapabilities})`|createBuffers|Takes 2 args. Method in class java.awt.Component.FlipBufferStrategy  Creates one or more complex, flipping buffers with the given  capabilities. |
|`CENTER_ALIGNMENT`|CENTER_ALIGNMENT|Takes 0 args. Static variable in class java.awt.Component  Ease-of-use constant for getAlignmentY and  getAlignmentX. |
|`checkImage(${1:Image}, ${2:ImageObserver})`|checkImage|Takes 2 args. Method in class java.awt.Component  Returns the status of the construction of a screen representation  of the specified image. |
|`coalesceEvents(${1:AWTEvent}, ${2:AWTEvent})`|coalesceEvents|Takes 2 args. Method in class java.awt.Component  Potentially coalesce an event being posted with an existing  event. |
|`contains()`|contains|Takes 0 args. Method in class java.awt.Component  Checks whether this component "contains" the specified point,  where the point's x and y coordinates are defined  to be relative to the coordinate system of this component. |
|`createImage()`|createImage|Takes 0 args. Method in class java.awt.Component  Creates an image from the specified image producer. |
|`createVolatileImage(${1:int}, ${2:int}, ${3:ImageCapabilities})`|createVolatileImage|Takes 3 args. Method in class java.awt.Component  Creates a volatile off-screen drawable image, with the given capabilities. |
|`createContext(${1:ColorModel}, ${2:ColorModel}, ${3:RenderingHints})`|createContext|Takes 3 args. Method in interface java.awt.Composite  Creates a context containing state that is used to perform  the compositing operation. |
|`compose(${1:Raster}, ${2:Raster}, ${3:WritableRaster})`|compose|Takes 3 args. Method in interface java.awt.CompositeContext  Composes the two source Raster objects and  places the result in the destination  WritableRaster. |
|`componentAdded()`|componentAdded|Takes 0 args. Method in class java.awt.Container.AccessibleAWTContainer.AccessibleContainerHandler  |
|`componentRemoved()`|componentRemoved|Takes 0 args. Method in class java.awt.Container.AccessibleAWTContainer.AccessibleContainerHandler  |
|`CROSSHAIR_CURSOR`|CROSSHAIR_CURSOR|Takes 0 args. Static variable in class java.awt.Cursor  The crosshair cursor type. |
|`CUSTOM_CURSOR`|CUSTOM_CURSOR|Takes 0 args. Static variable in class java.awt.Cursor  The type associated with all custom cursors. |
|`CAPS_LOCK`|CAPS_LOCK|Takes 0 args. Static variable in class java.awt.Event  The Caps Lock key, a non-ASCII action key. |
|`CTRL_MASK`|CTRL_MASK|Takes 0 args. Static variable in class java.awt.Event  This flag indicates that the Control key was down when the event  occurred. |
|`clickCount`|clickCount|Takes 0 args. Variable in class java.awt.Event  For MOUSE_DOWN events, this field indicates the  number of consecutive clicks. |
|`controlDown()`|controlDown|Takes 0 args. Method in class java.awt.Event  NOTE: The Event class is obsolete and is  available only for backwards compatilibility. |
|`createSecondaryLoop()`|createSecondaryLoop|Takes 0 args. Method in class java.awt.EventQueue  Creates a new secondary loop associated with this  event queue. |
|`CENTER`|CENTER|Takes 0 args. Static variable in class java.awt.FlowLayout  This value indicates that each row of components  should be centered. |
|`CENTER_BASELINE`|CENTER_BASELINE|Takes 0 args. Static variable in class java.awt.Font  The baseline used in ideographic scripts like Chinese, Japanese,  and Korean when laying out text. |
|`canDisplay()`|canDisplay|Takes 0 args. Method in class java.awt.Font  Checks if this Font has a glyph for the specified  character. |
|`canDisplayUpTo(${1:CharacterIterator}, ${2:int}, ${3:int})`|canDisplayUpTo|Takes 3 args. Method in class java.awt.Font  Indicates whether or not this Font can display the  text specified by the iter starting at  start and ending at limit. |
|`createFont(${1:int}, ${2:InputStream})`|createFont|Takes 2 args. Static method in class java.awt.Font  Returns a new Font using the specified font type  and input data. |
|`createGlyphVector(${1:FontRenderContext}, ${2:CharacterIterator})`|createGlyphVector|Takes 2 args. Method in class java.awt.Font  Creates a GlyphVector by  mapping the specified characters to glyphs one-to-one based on the  Unicode cmap in this Font. |
|`charWidth()`|charWidth|Takes 0 args. Method in class java.awt.FontMetrics  Returns the advance width of the specified character in this  Font. |
|`charsWidth(${1:char[]}, ${2:int}, ${3:int})`|charsWidth|Takes 3 args. Method in class java.awt.FontMetrics  Returns the total advance width for showing the specified array  of characters in this Font. |
|`createContext(${1:ColorModel}, ${2:Rectangle}, ${3:Rectangle2D}, ${4:AffineTransform}, ${5:RenderingHints})`|createContext|Takes 5 args. Method in class java.awt.GradientPaint  Creates and returns a PaintContext used to  generate a linear color gradient pattern. |
|`clearRect(${1:int}, ${2:int}, ${3:int}, ${4:int})`|clearRect|Takes 4 args. Method in class java.awt.Graphics  Clears the specified rectangle by filling it with the background  color of the current drawing surface. |
|`clipRect(${1:int}, ${2:int}, ${3:int}, ${4:int})`|clipRect|Takes 4 args. Method in class java.awt.Graphics  Intersects the current clip with the specified rectangle. |
|`copyArea(${1:int}, ${2:int}, ${3:int}, ${4:int}, ${5:int}, ${6:int})`|copyArea|Takes 6 args. Method in class java.awt.Graphics  Copies an area of the component by a distance specified by  dx and dy. |
|`create(${1:int}, ${2:int}, ${3:int}, ${4:int})`|create|Takes 4 args. Method in class java.awt.Graphics  Creates a new Graphics object based on this  Graphics object, but with a new translation and clip area. |
|`clip()`|clip|Takes 0 args. Method in class java.awt.Graphics2D  Intersects the current Clip with the interior of the  specified Shape and sets the Clip to the  resulting intersection. |
|`createCompatibleImage(${1:int}, ${2:int}, ${3:int})`|createCompatibleImage|Takes 3 args. Method in class java.awt.GraphicsConfiguration  Returns a BufferedImage that supports the specified  transparency and has a data layout and color model  compatible with this GraphicsConfiguration. |
|`createCompatibleVolatileImage(${1:int}, ${2:int}, ${3:ImageCapabilities}, ${4:int})`|createCompatibleVolatileImage|Takes 4 args. Method in class java.awt.GraphicsConfiguration  Returns a VolatileImage with a data layout and color model  compatible with this GraphicsConfiguration, using  the specified image capabilities and transparency value. |
|`createGraphics()`|createGraphics|Takes 0 args. Method in class java.awt.GraphicsEnvironment  Returns a Graphics2D object for rendering into the  specified BufferedImage. |
|`CENTER`|CENTER|Takes 0 args. Static variable in class java.awt.GridBagConstraints  Put the component in the center of its display area. |
|`clone()`|clone|Takes 0 args. Method in class java.awt.GridBagConstraints  Creates a copy of this grid bag constraint. |
|`columnWeights`|columnWeights|Takes 0 args. Variable in class java.awt.GridBagLayout  This field holds the overrides to the column weights. |
|`columnWidths`|columnWidths|Takes 0 args. Variable in class java.awt.GridBagLayout  This field holds the overrides to the column minimum  width. |
|`comptable`|comptable|Takes 0 args. Variable in class java.awt.GridBagLayout  This hashtable maintains the association between  a component and its gridbag constraints. |
|`clone()`|clone|Takes 0 args. Method in class java.awt.ImageCapabilities  |
|`clone()`|clone|Takes 0 args. Method in class java.awt.Insets  Create a copy of this object. |
|`COMMON`|COMMON|Takes 0 args. Static variable in class java.awt.JobAttributes.DialogType  The DialogType instance to use for  specifying the cross-platform, pure Java print dialog. |
|`clone()`|clone|Takes 0 args. Method in class java.awt.JobAttributes  Creates and returns a copy of this JobAttributes. |
|`clearGlobalFocusOwner()`|clearGlobalFocusOwner|Takes 0 args. Method in class java.awt.KeyboardFocusManager  Clears the global focus owner at both the Java and native levels. |
|`CENTER`|CENTER|Takes 0 args. Static variable in class java.awt.Label  Indicates that the label should be centered. |
|`createContext(${1:ColorModel}, ${2:Rectangle}, ${3:Rectangle2D}, ${4:AffineTransform}, ${5:RenderingHints})`|createContext|Takes 5 args. Method in class java.awt.LinearGradientPaint  Creates and returns a PaintContext used to  generate a linear color gradient pattern. |
|`contains()`|contains|Takes 0 args. Method in class java.awt.List.AccessibleAWTList.AccessibleAWTListChild  Checks whether the specified point is within this object's  bounds, where the point's x and y coordinates are defined to  be relative to the coordinate system of the object. |
|`clearAccessibleSelection()`|clearAccessibleSelection|Takes 0 args. Method in class java.awt.List.AccessibleAWTList  Clears the selection in the object, so that nothing in the  object is selected. |
|`COMPLETE`|COMPLETE|Takes 0 args. Static variable in class java.awt.MediaTracker  Flag indicating that the downloading of media was completed  successfully. |
|`checkAll()`|checkAll|Takes 0 args. Method in class java.awt.MediaTracker  Checks to see if all images being tracked by this media tracker  have finished loading. |
|`checkID(${1:int}, ${2:boolean})`|checkID|Takes 2 args. Method in class java.awt.MediaTracker  Checks to see if all images tracked by this media tracker that  are tagged with the specified identifier have finished loading. |
|`clearAccessibleSelection()`|clearAccessibleSelection|Takes 0 args. Method in class java.awt.MenuComponent.AccessibleAWTMenuComponent  Clears the selection in the object, so that no children in the  object are selected. |
|`contains()`|contains|Takes 0 args. Method in class java.awt.MenuComponent.AccessibleAWTMenuComponent  Checks whether the specified point is within this object's bounds,  where the point's x and y coordinates are defined to be relative to  the coordinate system of the object. |
|`COLOR`|COLOR|Takes 0 args. Static variable in class java.awt.PageAttributes.ColorType  The ColorType instance to use for specifying color printing. |
|`C0`|C0|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_C0. |
|`C1`|C1|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_C1. |
|`C10`|C10|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_C10. |
|`C2`|C2|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_C2. |
|`C3`|C3|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_C3. |
|`C4`|C4|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_C4. |
|`C5`|C5|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_C5. |
|`C6`|C6|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_C6. |
|`C7`|C7|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_C7. |
|`C8`|C8|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_C8. |
|`C9`|C9|Takes 0 args. Static variable in class java.awt.PageAttributes.MediaType  An alias for ISO_C9. |
|`clone()`|clone|Takes 0 args. Method in class java.awt.PageAttributes  Creates and returns a copy of this PageAttributes. |
|`createContext(${1:ColorModel}, ${2:Rectangle}, ${3:Rectangle2D}, ${4:AffineTransform}, ${5:RenderingHints})`|createContext|Takes 5 args. Method in interface java.awt.Paint  Creates and returns a PaintContext used to  generate the color pattern. |
|`contains()`|contains|Takes 0 args. Method in class java.awt.Polygon  Tests if the interior of the Shape entirely contains the  specified Rectangle2D. |
|`createContext(${1:ColorModel}, ${2:Rectangle}, ${3:Rectangle2D}, ${4:AffineTransform}, ${5:RenderingHints})`|createContext|Takes 5 args. Method in class java.awt.RadialGradientPaint  Creates and returns a PaintContext used to  generate a circular radial color gradient pattern. |
|`contains()`|contains|Takes 0 args. Method in class java.awt.Rectangle  Checks whether or not this Rectangle entirely contains  the specified Rectangle. |
|`createIntersection()`|createIntersection|Takes 0 args. Method in class java.awt.Rectangle  Returns a new Rectangle2D object representing the  intersection of this Rectangle2D with the specified  Rectangle2D. |
|`createUnion()`|createUnion|Takes 0 args. Method in class java.awt.Rectangle  Returns a new Rectangle2D object representing the  union of this Rectangle2D with the specified  Rectangle2D. |
|`clear()`|clear|Takes 0 args. Method in class java.awt.RenderingHints  Clears this RenderingHints object of all key/value  pairs. |
|`clone()`|clone|Takes 0 args. Method in class java.awt.RenderingHints  Creates a clone of this RenderingHints object  that has the same contents as this RenderingHints  object. |
|`containsKey()`|containsKey|Takes 0 args. Method in class java.awt.RenderingHints  Returns true if this RenderingHints   contains a mapping for the specified key. |
|`containsValue()`|containsValue|Takes 0 args. Method in class java.awt.RenderingHints  Returns true if this RenderingHints maps one or more keys to the  specified value. |
|`createScreenCapture()`|createScreenCapture|Takes 0 args. Method in class java.awt.Robot  Creates an image containing pixels read from the screen. |
|`contains()`|contains|Takes 0 args. Method in interface java.awt.Shape  Tests if the interior of the Shape entirely contains the  specified Rectangle2D. |
|`close()`|close|Takes 0 args. Method in class java.awt.SplashScreen  Hides the splash screen, closes the window, and releases all associated  resources. |
|`createGraphics()`|createGraphics|Takes 0 args. Method in class java.awt.SplashScreen  Creates a graphics context (as a Graphics2D object) for the splash  screen overlay image, which allows you to draw over the splash screen. |
|`createStrokedShape()`|createStrokedShape|Takes 0 args. Method in interface java.awt.Stroke  Returns an outline Shape which encloses the area that  should be painted when the Shape is stroked according  to the rules defined by the  object implementing the Stroke interface. |
|`CONTROL`|CONTROL|Takes 0 args. Static variable in class java.awt.SystemColor  The array index for the  SystemColor.control system color. |
|`CONTROL_DK_SHADOW`|CONTROL_DK_SHADOW|Takes 0 args. Static variable in class java.awt.SystemColor  The array index for the  SystemColor.controlDkShadow system color. |
|`CONTROL_HIGHLIGHT`|CONTROL_HIGHLIGHT|Takes 0 args. Static variable in class java.awt.SystemColor  The array index for the  SystemColor.controlHighlight system color. |
|`CONTROL_LT_HIGHLIGHT`|CONTROL_LT_HIGHLIGHT|Takes 0 args. Static variable in class java.awt.SystemColor  The array index for the  SystemColor.controlLtHighlight system color. |
|`CONTROL_SHADOW`|CONTROL_SHADOW|Takes 0 args. Static variable in class java.awt.SystemColor  The array index for the  SystemColor.controlShadow system color. |
|`CONTROL_TEXT`|CONTROL_TEXT|Takes 0 args. Static variable in class java.awt.SystemColor  The array index for the  SystemColor.controlText system color. |
|`control`|control|Takes 0 args. Static variable in class java.awt.SystemColor  The color rendered for the background of control panels and control objects,  such as pushbuttons. |
|`controlDkShadow`|controlDkShadow|Takes 0 args. Static variable in class java.awt.SystemColor  The color rendered for dark shadow areas on 3D control objects, such as pushbuttons. |
|`controlHighlight`|controlHighlight|Takes 0 args. Static variable in class java.awt.SystemColor  The color rendered for light areas of 3D control objects, such as pushbuttons. |
|`controlLtHighlight`|controlLtHighlight|Takes 0 args. Static variable in class java.awt.SystemColor  The color rendered for highlight areas of 3D control objects, such as pushbuttons. |
|`controlShadow`|controlShadow|Takes 0 args. Static variable in class java.awt.SystemColor  The color rendered for shadow areas of 3D control objects, such as pushbuttons. |
|`controlText`|controlText|Takes 0 args. Static variable in class java.awt.SystemColor  The color rendered for the text of control panels and control objects,  such as pushbuttons. |
|`createContext(${1:ColorModel}, ${2:Rectangle}, ${3:Rectangle2D}, ${4:AffineTransform}, ${5:RenderingHints})`|createContext|Takes 5 args. Method in class java.awt.TexturePaint  Creates and returns a PaintContext used to  generate a tiled image pattern. |
|`checkImage(${1:Image}, ${2:int}, ${3:int}, ${4:ImageObserver})`|checkImage|Takes 4 args. Method in class java.awt.Toolkit  Indicates the construction status of a specified image that is  being prepared for display. |
|`createButton()`|createButton|Takes 0 args. Method in class java.awt.Toolkit  Creates this toolkit's implementation of Button using  the specified peer interface. |
|`createCanvas()`|createCanvas|Takes 0 args. Method in class java.awt.Toolkit  Creates this toolkit's implementation of Canvas using  the specified peer interface. |
|`createCheckbox()`|createCheckbox|Takes 0 args. Method in class java.awt.Toolkit  Creates this toolkit's implementation of Checkbox using  the specified peer interface. |
|`createCheckboxMenuItem()`|createCheckboxMenuItem|Takes 0 args. Method in class java.awt.Toolkit  Creates this toolkit's implementation of CheckboxMenuItem using  the specified peer interface. |
|`createChoice()`|createChoice|Takes 0 args. Method in class java.awt.Toolkit  Creates this toolkit's implementation of Choice using  the specified peer interface. |
|`createComponent()`|createComponent|Takes 0 args. Method in class java.awt.Toolkit  Creates a peer for a component or container. |
|`createCustomCursor(${1:Image}, ${2:Point}, ${3:String})`|createCustomCursor|Takes 3 args. Method in class java.awt.Toolkit  Creates a new custom cursor object. |
|`createDesktopPeer()`|createDesktopPeer|Takes 0 args. Method in class java.awt.Toolkit  Creates this toolkit's implementation of the Desktop  using the specified peer interface. |
|`createDialog()`|createDialog|Takes 0 args. Method in class java.awt.Toolkit  Creates this toolkit's implementation of Dialog using  the specified peer interface. |
|`createDragGestureRecognizer(${1:Class}, ${2:DragSource}, ${3:Component}, ${4:int}, ${5:DragGestureListener})`|createDragGestureRecognizer|Takes 5 args. Method in class java.awt.Toolkit  Creates a concrete, platform dependent, subclass of the abstract  DragGestureRecognizer class requested, and associates it with the  DragSource, Component and DragGestureListener specified. |
|`createDragSourceContextPeer()`|createDragSourceContextPeer|Takes 0 args. Method in class java.awt.Toolkit  Creates the peer for a DragSourceContext. |
|`createFileDialog()`|createFileDialog|Takes 0 args. Method in class java.awt.Toolkit  Creates this toolkit's implementation of FileDialog using  the specified peer interface. |
|`createFrame()`|createFrame|Takes 0 args. Method in class java.awt.Toolkit  Creates this toolkit's implementation of Frame using  the specified peer interface. |
|`createImage()`|createImage|Takes 0 args. Method in class java.awt.Toolkit  Returns an image which gets pixel data from the specified URL. |
|`createLabel()`|createLabel|Takes 0 args. Method in class java.awt.Toolkit  Creates this toolkit's implementation of Label using  the specified peer interface. |
|`createList()`|createList|Takes 0 args. Method in class java.awt.Toolkit  Creates this toolkit's implementation of List using  the specified peer interface. |
|`createMenu()`|createMenu|Takes 0 args. Method in class java.awt.Toolkit  Creates this toolkit's implementation of Menu using  the specified peer interface. |
|`createMenuBar()`|createMenuBar|Takes 0 args. Method in class java.awt.Toolkit  Creates this toolkit's implementation of MenuBar using  the specified peer interface. |
|`createMenuItem()`|createMenuItem|Takes 0 args. Method in class java.awt.Toolkit  Creates this toolkit's implementation of MenuItem using  the specified peer interface. |
|`createPanel()`|createPanel|Takes 0 args. Method in class java.awt.Toolkit  Creates this toolkit's implementation of Panel using  the specified peer interface. |
|`createPopupMenu()`|createPopupMenu|Takes 0 args. Method in class java.awt.Toolkit  Creates this toolkit's implementation of PopupMenu using  the specified peer interface. |
|`createScrollPane()`|createScrollPane|Takes 0 args. Method in class java.awt.Toolkit  Creates this toolkit's implementation of ScrollPane using  the specified peer interface. |
|`createScrollbar()`|createScrollbar|Takes 0 args. Method in class java.awt.Toolkit  Creates this toolkit's implementation of Scrollbar using  the specified peer interface. |
|`createTextArea()`|createTextArea|Takes 0 args. Method in class java.awt.Toolkit  Creates this toolkit's implementation of TextArea using  the specified peer interface. |
|`createTextField()`|createTextField|Takes 0 args. Method in class java.awt.Toolkit  Creates this toolkit's implementation of TextField using  the specified peer interface. |
|`createWindow()`|createWindow|Takes 0 args. Method in class java.awt.Toolkit  Creates this toolkit's implementation of Window using  the specified peer interface. |
|`createBufferStrategy(${1:int}, ${2:BufferCapabilities})`|createBufferStrategy|Takes 2 args. Method in class java.awt.Window  Creates a new strategy for multi-buffering on this component with the  required buffer capabilities. |
|`CS_CIEXYZ`|CS_CIEXYZ|Takes 0 args. Static variable in class java.awt.color.ColorSpace  The CIEXYZ conversion color space defined above. |
|`CS_GRAY`|CS_GRAY|Takes 0 args. Static variable in class java.awt.color.ColorSpace  The built-in linear gray scale color space. |
|`CS_LINEAR_RGB`|CS_LINEAR_RGB|Takes 0 args. Static variable in class java.awt.color.ColorSpace  A built-in linear RGB color space. |
|`CS_PYCC`|CS_PYCC|Takes 0 args. Static variable in class java.awt.color.ColorSpace  The Photo YCC conversion color space. |
|`CS_sRGB`|CS_sRGB|Takes 0 args. Static variable in class java.awt.color.ColorSpace  The sRGB color space defined at    http://www.w3.org/pub/WWW/Graphics/Color/sRGB.html  . |
|`CLASS_ABSTRACT`|CLASS_ABSTRACT|Takes 0 args. Static variable in class java.awt.color.ICC_Profile  Profile class is abstract. |
|`CLASS_COLORSPACECONVERSION`|CLASS_COLORSPACECONVERSION|Takes 0 args. Static variable in class java.awt.color.ICC_Profile  Profile class is color space conversion. |
|`CLASS_DEVICELINK`|CLASS_DEVICELINK|Takes 0 args. Static variable in class java.awt.color.ICC_Profile  Profile class is device link. |
|`CLASS_DISPLAY`|CLASS_DISPLAY|Takes 0 args. Static variable in class java.awt.color.ICC_Profile  Profile class is display. |
|`CLASS_INPUT`|CLASS_INPUT|Takes 0 args. Static variable in class java.awt.color.ICC_Profile  Profile class is input. |
|`CLASS_NAMEDCOLOR`|CLASS_NAMEDCOLOR|Takes 0 args. Static variable in class java.awt.color.ICC_Profile  Profile class is named color. |
|`CLASS_OUTPUT`|CLASS_OUTPUT|Takes 0 args. Static variable in class java.awt.color.ICC_Profile  Profile class is output. |
|`contents`|contents|Takes 0 args. Variable in class java.awt.datatransfer.Clipboard  |
|`clone()`|clone|Takes 0 args. Method in class java.awt.datatransfer.DataFlavor  Returns a clone of this DataFlavor. |
|`component`|component|Takes 0 args. Variable in class java.awt.dnd.DragGestureRecognizer  The Component  associated with this DragGestureRecognizer. |
|`createDefaultDragGestureRecognizer(${1:Component}, ${2:int}, ${3:DragGestureListener})`|createDefaultDragGestureRecognizer|Takes 3 args. Method in class java.awt.dnd.DragSource  Creates a new DragGestureRecognizer  that implements the default  abstract subclass of DragGestureRecognizer  for this DragSource,  and sets the specified Component  and DragGestureListener on the  newly created object. |
|`createDragGestureRecognizer(${1:Class}, ${2:Component}, ${3:int}, ${4:DragGestureListener})`|createDragGestureRecognizer|Takes 4 args. Method in class java.awt.dnd.DragSource  Creates a new DragGestureRecognizer  that implements the specified  abstract subclass of  DragGestureRecognizer, and  sets the specified Component  and DragGestureListener on  the newly created object. |
|`createDragSourceContext(${1:DragSourceContextPeer}, ${2:DragGestureEvent}, ${3:Cursor}, ${4:Image}, ${5:Point}, ${6:Transferable}, ${7:DragSourceListener})`|createDragSourceContext|Takes 7 args. Method in class java.awt.dnd.DragSource  Creates the DragSourceContext to handle the current drag  operation. |
|`CHANGED`|CHANGED|Takes 0 args. Static variable in class java.awt.dnd.DragSourceContext  An int used by updateCurrentCursor()  indicating that the user operation has changed. |
|`clearAutoscroll()`|clearAutoscroll|Takes 0 args. Method in class java.awt.dnd.DropTarget  clear autoscrolling |
|`createDropTargetAutoScroller(${1:Component}, ${2:Point})`|createDropTargetAutoScroller|Takes 2 args. Method in class java.awt.dnd.DropTarget  create an embedded autoscroller |
|`createDropTargetContext()`|createDropTargetContext|Takes 0 args. Method in class java.awt.dnd.DropTarget  Creates the DropTargetContext associated with this DropTarget. |
|`createTransferableProxy(${1:Transferable}, ${2:boolean})`|createTransferableProxy|Takes 2 args. Method in class java.awt.dnd.DropTargetContext  Creates a TransferableProxy to proxy for the specified  Transferable. |
|`context`|context|Takes 0 args. Variable in class java.awt.dnd.DropTargetEvent  The DropTargetContext associated with this  DropTargetEvent. |
|`CTRL_MASK`|CTRL_MASK|Takes 0 args. Static variable in class java.awt.event.ActionEvent  The control modifier. |
|`componentHidden()`|componentHidden|Takes 0 args. Method in class java.awt.event.ComponentAdapter  Invoked when the component has been made invisible. |
|`componentMoved()`|componentMoved|Takes 0 args. Method in class java.awt.event.ComponentAdapter  Invoked when the component's position changes. |
|`componentResized()`|componentResized|Takes 0 args. Method in class java.awt.event.ComponentAdapter  Invoked when the component's size changes. |
|`componentShown()`|componentShown|Takes 0 args. Method in class java.awt.event.ComponentAdapter  Invoked when the component has been made visible. |
|`COMPONENT_FIRST`|COMPONENT_FIRST|Takes 0 args. Static variable in class java.awt.event.ComponentEvent  The first number in the range of ids used for component events. |
|`COMPONENT_HIDDEN`|COMPONENT_HIDDEN|Takes 0 args. Static variable in class java.awt.event.ComponentEvent  This event indicates that the component was rendered invisible. |
|`COMPONENT_LAST`|COMPONENT_LAST|Takes 0 args. Static variable in class java.awt.event.ComponentEvent  The last number in the range of ids used for component events. |
|`COMPONENT_MOVED`|COMPONENT_MOVED|Takes 0 args. Static variable in class java.awt.event.ComponentEvent  This event indicates that the component's position changed. |
|`COMPONENT_RESIZED`|COMPONENT_RESIZED|Takes 0 args. Static variable in class java.awt.event.ComponentEvent  This event indicates that the component's size changed. |
|`COMPONENT_SHOWN`|COMPONENT_SHOWN|Takes 0 args. Static variable in class java.awt.event.ComponentEvent  This event indicates that the component was made visible. |
|`componentHidden()`|componentHidden|Takes 0 args. Method in interface java.awt.event.ComponentListener  Invoked when the component has been made invisible. |
|`componentMoved()`|componentMoved|Takes 0 args. Method in interface java.awt.event.ComponentListener  Invoked when the component's position changes. |
|`componentResized()`|componentResized|Takes 0 args. Method in interface java.awt.event.ComponentListener  Invoked when the component's size changes. |
|`componentShown()`|componentShown|Takes 0 args. Method in interface java.awt.event.ComponentListener  Invoked when the component has been made visible. |
|`componentAdded()`|componentAdded|Takes 0 args. Method in class java.awt.event.ContainerAdapter  Invoked when a component has been added to the container. |
|`componentRemoved()`|componentRemoved|Takes 0 args. Method in class java.awt.event.ContainerAdapter  Invoked when a component has been removed from the container. |
|`COMPONENT_ADDED`|COMPONENT_ADDED|Takes 0 args. Static variable in class java.awt.event.ContainerEvent  This event indicates that a component was added to the container. |
|`COMPONENT_REMOVED`|COMPONENT_REMOVED|Takes 0 args. Static variable in class java.awt.event.ContainerEvent  This event indicates that a component was removed from the container. |
|`CONTAINER_FIRST`|CONTAINER_FIRST|Takes 0 args. Static variable in class java.awt.event.ContainerEvent  The first number in the range of ids used for container events. |
|`CONTAINER_LAST`|CONTAINER_LAST|Takes 0 args. Static variable in class java.awt.event.ContainerEvent  The last number in the range of ids used for container events. |
|`componentAdded()`|componentAdded|Takes 0 args. Method in interface java.awt.event.ContainerListener  Invoked when a component has been added to the container. |
|`componentRemoved()`|componentRemoved|Takes 0 args. Method in interface java.awt.event.ContainerListener  Invoked when a component has been removed from the container. |
|`CTRL_DOWN_MASK`|CTRL_DOWN_MASK|Takes 0 args. Static variable in class java.awt.event.InputEvent  The Control key extended modifier constant. |
|`CTRL_MASK`|CTRL_MASK|Takes 0 args. Static variable in class java.awt.event.InputEvent  The Control key modifier constant. |
|`consume()`|consume|Takes 0 args. Method in class java.awt.event.InputEvent  Consumes this event so that it will not be processed  in the default manner by the source which originated it. |
|`CARET_POSITION_CHANGED`|CARET_POSITION_CHANGED|Takes 0 args. Static variable in class java.awt.event.InputMethodEvent  The event type indicating a changed insertion point in input method text. |
|`consume()`|consume|Takes 0 args. Method in class java.awt.event.InputMethodEvent  Consumes this event so that it will not be processed  in the default manner by the source which originated it. |
|`caretPositionChanged()`|caretPositionChanged|Takes 0 args. Method in interface java.awt.event.InputMethodListener  Invoked when the caret within composed text has changed. |
|`catchExceptions`|catchExceptions|Takes 0 args. Variable in class java.awt.event.InvocationEvent  Set to true if dispatch() catches Throwable and stores it in the  exception instance variable. |
|`CHAR_UNDEFINED`|CHAR_UNDEFINED|Takes 0 args. Static variable in class java.awt.event.KeyEvent  KEY_PRESSED and KEY_RELEASED events which do not map to a  valid Unicode character use this for the keyChar value. |
|`COMBINING`|COMBINING|Takes 0 args. Static variable in class java.awt.font.GlyphMetrics  Indicates a glyph that represents a combining character,  such as an umlaut. |
|`COMPONENT`|COMPONENT|Takes 0 args. Static variable in class java.awt.font.GlyphMetrics  Indicates a glyph with no corresponding character in the  backing store. |
|`CENTER_BASELINE`|CENTER_BASELINE|Takes 0 args. Static variable in class java.awt.font.GraphicAttribute  Aligns origin of graphic to center baseline of line. |
|`CHAR_REPLACEMENT`|CHAR_REPLACEMENT|Takes 0 args. Static variable in class java.awt.font.TextAttribute  Attribute key for a user-defined glyph to display in lieu  of the font's standard glyph for a character. |
|`clone()`|clone|Takes 0 args. Method in class java.awt.font.TextLayout  Creates a copy of this TextLayout. |
|`clone()`|clone|Takes 0 args. Method in class java.awt.font.TextMeasurer  |
|`clone()`|clone|Takes 0 args. Method in class java.awt.geom.AffineTransform  Returns a copy of this AffineTransform object. |
|`concatenate()`|concatenate|Takes 0 args. Method in class java.awt.geom.AffineTransform  Concatenates an AffineTransform Tx to  this AffineTransform Cx in the most commonly useful  way to provide a new user space  that is mapped to the former user space by Tx. |
|`createInverse()`|createInverse|Takes 0 args. Method in class java.awt.geom.AffineTransform  Returns an AffineTransform object representing the  inverse transformation. |
|`createTransformedShape()`|createTransformedShape|Takes 0 args. Method in class java.awt.geom.AffineTransform  Returns a new Shape object defined by the geometry of the  specified Shape after it has been transformed by  this transform. |
|`CHORD`|CHORD|Takes 0 args. Static variable in class java.awt.geom.Arc2D  The closure type for an arc closed by drawing a straight  line segment from the start of the arc segment to the end of the  arc segment. |
|`contains()`|contains|Takes 0 args. Method in class java.awt.geom.Arc2D  Determines whether or not the interior of the arc entirely contains  the specified rectangle. |
|`containsAngle()`|containsAngle|Takes 0 args. Method in class java.awt.geom.Arc2D  Determines whether or not the specified angle is within the  angular extents of the arc. |
|`clone()`|clone|Takes 0 args. Method in class java.awt.geom.Area  Returns an exact copy of this Area object. |
|`contains()`|contains|Takes 0 args. Method in class java.awt.geom.Area  Tests if the interior of the Shape entirely contains the  specified Rectangle2D. |
|`createTransformedArea()`|createTransformedArea|Takes 0 args. Method in class java.awt.geom.Area  Creates a new Area object that contains the same  geometry as this Area transformed by the specified  AffineTransform. |
|`ctrlx1`|ctrlx1|Takes 0 args. Variable in class java.awt.geom.CubicCurve2D.Double  The X coordinate of the first control point  of the cubic curve segment. |
|`ctrlx2`|ctrlx2|Takes 0 args. Variable in class java.awt.geom.CubicCurve2D.Double  The X coordinate of the second control point  of the cubic curve segment. |
|`ctrly1`|ctrly1|Takes 0 args. Variable in class java.awt.geom.CubicCurve2D.Double  The Y coordinate of the first control point  of the cubic curve segment. |
|`ctrly2`|ctrly2|Takes 0 args. Variable in class java.awt.geom.CubicCurve2D.Double  The Y coordinate of the second control point  of the cubic curve segment. |
|`ctrlx1`|ctrlx1|Takes 0 args. Variable in class java.awt.geom.CubicCurve2D.Float  The X coordinate of the first control point  of the cubic curve segment. |
|`ctrlx2`|ctrlx2|Takes 0 args. Variable in class java.awt.geom.CubicCurve2D.Float  The X coordinate of the second control point  of the cubic curve segment. |
|`ctrly1`|ctrly1|Takes 0 args. Variable in class java.awt.geom.CubicCurve2D.Float  The Y coordinate of the first control point  of the cubic curve segment. |
|`ctrly2`|ctrly2|Takes 0 args. Variable in class java.awt.geom.CubicCurve2D.Float  The Y coordinate of the second control point  of the cubic curve segment. |
|`clone()`|clone|Takes 0 args. Method in class java.awt.geom.CubicCurve2D  Creates a new object of the same class as this object. |
|`contains()`|contains|Takes 0 args. Method in class java.awt.geom.CubicCurve2D  Tests if the interior of the Shape entirely contains the  specified Rectangle2D. |
|`clone()`|clone|Takes 0 args. Method in class java.awt.geom.Dimension2D  Creates a new object of the same class as this object. |
|`contains(${1:double}, ${2:double}, ${3:double}, ${4:double})`|contains|Takes 4 args. Method in class java.awt.geom.Ellipse2D  Tests if the interior of the Shape entirely contains  the specified rectangular area. |
|`currentSegment()`|currentSegment|Takes 0 args. Method in class java.awt.geom.FlatteningPathIterator  Returns the coordinates and type of the current path segment in  the iteration. |
|`clone()`|clone|Takes 0 args. Method in class java.awt.geom.Line2D  Creates a new object of the same class as this object. |
|`contains()`|contains|Takes 0 args. Method in class java.awt.geom.Line2D  Tests if the interior of this Line2D entirely contains  the specified Rectangle2D. |
|`clone()`|clone|Takes 0 args. Method in class java.awt.geom.Path2D.Double  Creates a new object of the same class as this object. |
|`curveTo(${1:double}, ${2:double}, ${3:double}, ${4:double}, ${5:double}, ${6:double})`|curveTo|Takes 6 args. Method in class java.awt.geom.Path2D.Double  Adds a curved segment, defined by three new points, to the path by  drawing a B&eacute;zier curve that intersects both the current  coordinates and the specified coordinates (x3,y3),  using the specified points (x1,y1) and (x2,y2) as  B&eacute;zier control points. |
|`clone()`|clone|Takes 0 args. Method in class java.awt.geom.Path2D.Float  Creates a new object of the same class as this object. |
|`curveTo(${1:float}, ${2:float}, ${3:float}, ${4:float}, ${5:float}, ${6:float})`|curveTo|Takes 6 args. Method in class java.awt.geom.Path2D.Float  Adds a curved segment, defined by three new points, to the path by  drawing a B&eacute;zier curve that intersects both the current  coordinates and the specified coordinates (x3,y3),  using the specified points (x1,y1) and (x2,y2) as  B&eacute;zier control points. |
|`clone()`|clone|Takes 0 args. Method in class java.awt.geom.Path2D  Creates a new object of the same class as this object. |
|`closePath()`|closePath|Takes 0 args. Method in class java.awt.geom.Path2D  Closes the current subpath by drawing a straight line back to  the coordinates of the last moveTo. |
|`contains()`|contains|Takes 0 args. Method in class java.awt.geom.Path2D  Tests if the interior of the Shape entirely contains the  specified Rectangle2D. |
|`contains(${1:PathIterator}, ${2:Rectangle2D})`|contains|Takes 2 args. Static method in class java.awt.geom.Path2D  Tests if the specified Rectangle2D is entirely inside the  closed boundary of the specified PathIterator. |
|`createTransformedShape()`|createTransformedShape|Takes 0 args. Method in class java.awt.geom.Path2D  Returns a new Shape representing a transformed version  of this Path2D. |
|`curveTo(${1:double}, ${2:double}, ${3:double}, ${4:double}, ${5:double}, ${6:double})`|curveTo|Takes 6 args. Method in class java.awt.geom.Path2D  Adds a curved segment, defined by three new points, to the path by  drawing a B&eacute;zier curve that intersects both the current  coordinates and the specified coordinates (x3,y3),  using the specified points (x1,y1) and (x2,y2) as  B&eacute;zier control points. |
|`currentSegment()`|currentSegment|Takes 0 args. Method in interface java.awt.geom.PathIterator  Returns the coordinates and type of the current path segment in  the iteration. |
|`clone()`|clone|Takes 0 args. Method in class java.awt.geom.Point2D  Creates a new object of the same class and with the  same contents as this object. |
|`ctrlx`|ctrlx|Takes 0 args. Variable in class java.awt.geom.QuadCurve2D.Double  The X coordinate of the control point of the quadratic curve  segment. |
|`ctrly`|ctrly|Takes 0 args. Variable in class java.awt.geom.QuadCurve2D.Double  The Y coordinate of the control point of the quadratic curve  segment. |
|`ctrlx`|ctrlx|Takes 0 args. Variable in class java.awt.geom.QuadCurve2D.Float  The X coordinate of the control point of the quadratic curve  segment. |
|`ctrly`|ctrly|Takes 0 args. Variable in class java.awt.geom.QuadCurve2D.Float  The Y coordinate of the control point of the quadratic curve  segment. |
|`clone()`|clone|Takes 0 args. Method in class java.awt.geom.QuadCurve2D  Creates a new object of the same class and with the same contents  as this object. |
|`contains()`|contains|Takes 0 args. Method in class java.awt.geom.QuadCurve2D  Tests if the interior of the Shape entirely contains the  specified Rectangle2D. |
|`createIntersection()`|createIntersection|Takes 0 args. Method in class java.awt.geom.Rectangle2D.Double  Returns a new Rectangle2D object representing the  intersection of this Rectangle2D with the specified  Rectangle2D. |
|`createUnion()`|createUnion|Takes 0 args. Method in class java.awt.geom.Rectangle2D.Double  Returns a new Rectangle2D object representing the  union of this Rectangle2D with the specified  Rectangle2D. |
|`createIntersection()`|createIntersection|Takes 0 args. Method in class java.awt.geom.Rectangle2D.Float  Returns a new Rectangle2D object representing the  intersection of this Rectangle2D with the specified  Rectangle2D. |
|`createUnion()`|createUnion|Takes 0 args. Method in class java.awt.geom.Rectangle2D.Float  Returns a new Rectangle2D object representing the  union of this Rectangle2D with the specified  Rectangle2D. |
|`contains(${1:double}, ${2:double}, ${3:double}, ${4:double})`|contains|Takes 4 args. Method in class java.awt.geom.Rectangle2D  Tests if the interior of the Shape entirely contains  the specified rectangular area. |
|`createIntersection()`|createIntersection|Takes 0 args. Method in class java.awt.geom.Rectangle2D  Returns a new Rectangle2D object representing the  intersection of this Rectangle2D with the specified  Rectangle2D. |
|`createUnion()`|createUnion|Takes 0 args. Method in class java.awt.geom.Rectangle2D  Returns a new Rectangle2D object representing the  union of this Rectangle2D with the specified  Rectangle2D. |
|`clone()`|clone|Takes 0 args. Method in class java.awt.geom.RectangularShape  Creates a new object of the same class and with the same  contents as this object. |
|`contains()`|contains|Takes 0 args. Method in class java.awt.geom.RectangularShape  Tests if the interior of the Shape entirely contains the  specified Rectangle2D. |
|`contains(${1:double}, ${2:double}, ${3:double}, ${4:double})`|contains|Takes 4 args. Method in class java.awt.geom.RoundRectangle2D  Tests if the interior of the Shape entirely contains  the specified rectangular area. |
|`CONVERTED_TEXT`|CONVERTED_TEXT|Takes 0 args. Static variable in class java.awt.im.InputMethodHighlight  Constant for the converted text state. |
|`cancelLatestCommittedText()`|cancelLatestCommittedText|Takes 0 args. Method in interface java.awt.im.InputMethodRequests  Gets the latest committed text from the text editing component and  removes it from the component's text body. |
|`createInputMethodJFrame(${1:String}, ${2:boolean})`|createInputMethodJFrame|Takes 2 args. Method in interface java.awt.im.spi.InputMethodContext  Creates a top-level Swing JFrame for use by the input method. |
|`createInputMethodWindow(${1:String}, ${2:boolean})`|createInputMethodWindow|Takes 2 args. Method in interface java.awt.im.spi.InputMethodContext  Creates a top-level window for use by the input method. |
|`createInputMethod()`|createInputMethod|Takes 0 args. Method in interface java.awt.im.spi.InputMethodDescriptor  Creates a new instance of the corresponding input method. |
|`createCompatibleDestImage(${1:BufferedImage}, ${2:ColorModel})`|createCompatibleDestImage|Takes 2 args. Method in class java.awt.image.AffineTransformOp  Creates a zeroed destination image with the correct size and number of  bands. |
|`createCompatibleDestRaster()`|createCompatibleDestRaster|Takes 0 args. Method in class java.awt.image.AffineTransformOp  Creates a zeroed destination Raster with the correct size  and number of bands. |
|`createCompatibleDestRaster()`|createCompatibleDestRaster|Takes 0 args. Method in class java.awt.image.BandCombineOp  Creates a zeroed destination Raster with the correct size  and number of bands. |
|`createCompatibleSampleModel(${1:int}, ${2:int})`|createCompatibleSampleModel|Takes 2 args. Method in class java.awt.image.BandedSampleModel  Creates a new BandedSampleModel with the specified  width and height. |
|`createDataBuffer()`|createDataBuffer|Takes 0 args. Method in class java.awt.image.BandedSampleModel  Creates a DataBuffer that corresponds to this BandedSampleModel,  The DataBuffer's data type, number of banks, and size  will be consistent with this BandedSampleModel. |
|`createSubsetSampleModel()`|createSubsetSampleModel|Takes 0 args. Method in class java.awt.image.BandedSampleModel  Creates a new BandedSampleModel with a subset of the bands of this  BandedSampleModel. |
|`contentsLost()`|contentsLost|Takes 0 args. Method in class java.awt.image.BufferStrategy  Returns whether the drawing buffer was lost since the last call to  getDrawGraphics. |
|`contentsRestored()`|contentsRestored|Takes 0 args. Method in class java.awt.image.BufferStrategy  Returns whether the drawing buffer was recently restored from a lost  state and reinitialized to the default background color (white). |
|`coerceData()`|coerceData|Takes 0 args. Method in class java.awt.image.BufferedImage  Forces the data to match the state specified in the  isAlphaPremultiplied variable. |
|`copyData()`|copyData|Takes 0 args. Method in class java.awt.image.BufferedImage  Computes an arbitrary rectangular region of the  BufferedImage and copies it into a specified  WritableRaster. |
|`createGraphics()`|createGraphics|Takes 0 args. Method in class java.awt.image.BufferedImage  Creates a Graphics2D, which can be used to draw into  this BufferedImage. |
|`createCompatibleDestImage(${1:BufferedImage}, ${2:ColorModel})`|createCompatibleDestImage|Takes 2 args. Method in interface java.awt.image.BufferedImageOp  Creates a zeroed destination image with the correct size and number of  bands. |
|`createCompatibleDestImage(${1:BufferedImage}, ${2:ColorModel})`|createCompatibleDestImage|Takes 2 args. Method in class java.awt.image.ColorConvertOp  Creates a zeroed destination image with the correct size and number of  bands, given this source. |
|`createCompatibleDestRaster()`|createCompatibleDestRaster|Takes 0 args. Method in class java.awt.image.ColorConvertOp  Creates a zeroed destination Raster with the correct size and number of  bands, given this source. |
|`coerceData(${1:WritableRaster}, ${2:boolean})`|coerceData|Takes 2 args. Method in class java.awt.image.ColorModel  Forces the raster data to match the state specified in the  isAlphaPremultiplied variable, assuming the data is  currently correctly described by this ColorModel. |
|`createCompatibleSampleModel(${1:int}, ${2:int})`|createCompatibleSampleModel|Takes 2 args. Method in class java.awt.image.ColorModel  Creates a SampleModel with the specified width and  height that has a data layout compatible with this  ColorModel. |
|`createCompatibleWritableRaster(${1:int}, ${2:int})`|createCompatibleWritableRaster|Takes 2 args. Method in class java.awt.image.ColorModel  Creates a WritableRaster with the specified width and  height that has a data layout (SampleModel) compatible  with this ColorModel. |
|`coerceData(${1:WritableRaster}, ${2:boolean})`|coerceData|Takes 2 args. Method in class java.awt.image.ComponentColorModel  Forces the raster data to match the state specified in the  isAlphaPremultiplied variable, assuming the data  is currently correctly described by this ColorModel. |
|`createCompatibleSampleModel(${1:int}, ${2:int})`|createCompatibleSampleModel|Takes 2 args. Method in class java.awt.image.ComponentColorModel  Creates a SampleModel with the specified width and height,  that  has a data layout compatible with this ColorModel. |
|`createCompatibleWritableRaster(${1:int}, ${2:int})`|createCompatibleWritableRaster|Takes 2 args. Method in class java.awt.image.ComponentColorModel  Creates a WritableRaster with the specified width and height,  that  has a data layout (SampleModel) compatible with  this ColorModel. |
|`createCompatibleSampleModel(${1:int}, ${2:int})`|createCompatibleSampleModel|Takes 2 args. Method in class java.awt.image.ComponentSampleModel  Creates a new ComponentSampleModel with the specified  width and height. |
|`createDataBuffer()`|createDataBuffer|Takes 0 args. Method in class java.awt.image.ComponentSampleModel  Creates a DataBuffer that corresponds to this  ComponentSampleModel. |
|`createSubsetSampleModel()`|createSubsetSampleModel|Takes 0 args. Method in class java.awt.image.ComponentSampleModel  Creates a new ComponentSampleModel with a subset of the bands  of this ComponentSampleModel. |
|`createCompatibleDestImage(${1:BufferedImage}, ${2:ColorModel})`|createCompatibleDestImage|Takes 2 args. Method in class java.awt.image.ConvolveOp  Creates a zeroed destination image with the correct size and number  of bands. |
|`createCompatibleDestRaster()`|createCompatibleDestRaster|Takes 0 args. Method in class java.awt.image.ConvolveOp  Creates a zeroed destination Raster with the correct size and number  of bands, given this source. |
|`coerceData(${1:WritableRaster}, ${2:boolean})`|coerceData|Takes 2 args. Method in class java.awt.image.DirectColorModel  Forces the raster data to match the state specified in the  isAlphaPremultiplied variable, assuming the data is  currently correctly described by this ColorModel. |
|`createCompatibleWritableRaster(${1:int}, ${2:int})`|createCompatibleWritableRaster|Takes 2 args. Method in class java.awt.image.DirectColorModel  Creates a WritableRaster with the specified width and  height that has a data layout (SampleModel) compatible  with this ColorModel. |
|`COMPLETESCANLINES`|COMPLETESCANLINES|Takes 0 args. Static variable in interface java.awt.image.ImageConsumer  The pixels will be delivered in (multiples of) complete scanlines  at a time. |
|`clone()`|clone|Takes 0 args. Method in class java.awt.image.ImageFilter  Clones this object. |
|`consumer`|consumer|Takes 0 args. Variable in class java.awt.image.ImageFilter  The consumer of the particular image data stream for which this  instance of the ImageFilter is filtering data. |
|`convertToIntDiscrete(${1:Raster}, ${2:boolean})`|convertToIntDiscrete|Takes 2 args. Method in class java.awt.image.IndexColorModel  Returns a new BufferedImage of TYPE_INT_ARGB or  TYPE_INT_RGB that has a Raster with pixel data  computed by expanding the indices in the source Raster  using the color/alpha component arrays of this ColorModel. |
|`createCompatibleSampleModel(${1:int}, ${2:int})`|createCompatibleSampleModel|Takes 2 args. Method in class java.awt.image.IndexColorModel  Creates a SampleModel with the specified  width and height that has a data layout compatible with  this ColorModel. |
|`createCompatibleWritableRaster(${1:int}, ${2:int})`|createCompatibleWritableRaster|Takes 2 args. Method in class java.awt.image.IndexColorModel  Creates a WritableRaster with the specified width  and height that has a data layout (SampleModel)  compatible with this ColorModel. |
|`clone()`|clone|Takes 0 args. Method in class java.awt.image.Kernel  Clones this object. |
|`createCompatibleDestImage(${1:BufferedImage}, ${2:ColorModel})`|createCompatibleDestImage|Takes 2 args. Method in class java.awt.image.LookupOp  Creates a zeroed destination image with the correct size and number of  bands. |
|`createCompatibleDestRaster()`|createCompatibleDestRaster|Takes 0 args. Method in class java.awt.image.LookupOp  Creates a zeroed-destination Raster with the  correct size and number of bands, given this source. |
|`createCompatibleSampleModel(${1:int}, ${2:int})`|createCompatibleSampleModel|Takes 2 args. Method in class java.awt.image.MultiPixelPackedSampleModel  Creates a new MultiPixelPackedSampleModel with the  specified width and height. |
|`createDataBuffer()`|createDataBuffer|Takes 0 args. Method in class java.awt.image.MultiPixelPackedSampleModel  Creates a DataBuffer that corresponds to this  MultiPixelPackedSampleModel. |
|`createSubsetSampleModel()`|createSubsetSampleModel|Takes 0 args. Method in class java.awt.image.MultiPixelPackedSampleModel  Creates a new MultiPixelPackedSampleModel with a  subset of the bands of this  MultiPixelPackedSampleModel. |
|`createCompatibleSampleModel(${1:int}, ${2:int})`|createCompatibleSampleModel|Takes 2 args. Method in class java.awt.image.PackedColorModel  Creates a SampleModel with the specified width and  height that has a data layout compatible with this  ColorModel. |
|`createCompatibleSampleModel(${1:int}, ${2:int})`|createCompatibleSampleModel|Takes 2 args. Method in class java.awt.image.PixelInterleavedSampleModel  Creates a new PixelInterleavedSampleModel with the specified  width and height. |
|`createSubsetSampleModel()`|createSubsetSampleModel|Takes 0 args. Method in class java.awt.image.PixelInterleavedSampleModel  Creates a new PixelInterleavedSampleModel with a subset of the  bands of this PixelInterleavedSampleModel. |
|`canFilterIndexColorModel`|canFilterIndexColorModel|Takes 0 args. Variable in class java.awt.image.RGBImageFilter  This boolean indicates whether or not it is acceptable to apply  the color filtering of the filterRGB method to the color table  entries of an IndexColorModel object in lieu of pixel by pixel  filtering. |
|`createBandedRaster(${1:DataBuffer}, ${2:int}, ${3:int}, ${4:int}, ${5:int[]}, ${6:int[]}, ${7:Point})`|createBandedRaster|Takes 7 args. Static method in class java.awt.image.Raster  Creates a Raster based on a BandedSampleModel with the  specified DataBuffer, width, height, scanline stride, bank  indices, and band offsets. |
|`createChild(${1:int}, ${2:int}, ${3:int}, ${4:int}, ${5:int}, ${6:int}, ${7:int[]})`|createChild|Takes 7 args. Method in class java.awt.image.Raster  Returns a new Raster which shares all or part of this Raster's  DataBuffer. |
|`createCompatibleWritableRaster()`|createCompatibleWritableRaster|Takes 0 args. Method in class java.awt.image.Raster  Create a compatible WritableRaster with location (minX, minY)  and size (width, height) specified by rect, a  new SampleModel, and a new initialized DataBuffer. |
|`createInterleavedRaster(${1:DataBuffer}, ${2:int}, ${3:int}, ${4:int}, ${5:int}, ${6:int[]}, ${7:Point})`|createInterleavedRaster|Takes 7 args. Static method in class java.awt.image.Raster  Creates a Raster based on a PixelInterleavedSampleModel with the  specified DataBuffer, width, height, scanline stride, pixel  stride, and band offsets. |
|`createPackedRaster(${1:DataBuffer}, ${2:int}, ${3:int}, ${4:int}, ${5:Point})`|createPackedRaster|Takes 5 args. Static method in class java.awt.image.Raster  Creates a Raster based on a MultiPixelPackedSampleModel with the  specified DataBuffer, width, height, and bits per pixel. |
|`createRaster(${1:SampleModel}, ${2:DataBuffer}, ${3:Point})`|createRaster|Takes 3 args. Static method in class java.awt.image.Raster  Creates a Raster with the specified SampleModel and DataBuffer. |
|`createTranslatedChild(${1:int}, ${2:int})`|createTranslatedChild|Takes 2 args. Method in class java.awt.image.Raster  Create a Raster with the same size, SampleModel and DataBuffer  as this one, but with a different location. |
|`createWritableRaster(${1:SampleModel}, ${2:DataBuffer}, ${3:Point})`|createWritableRaster|Takes 3 args. Static method in class java.awt.image.Raster  Creates a WritableRaster with the specified SampleModel and DataBuffer. |
|`createCompatibleDestRaster()`|createCompatibleDestRaster|Takes 0 args. Method in interface java.awt.image.RasterOp  Creates a zeroed destination Raster with the correct size and number of  bands. |
|`copyData()`|copyData|Takes 0 args. Method in interface java.awt.image.RenderedImage  Computes an arbitrary rectangular region of the RenderedImage  and copies it into a caller-supplied WritableRaster. |
|`createCompatibleDestImage(${1:BufferedImage}, ${2:ColorModel})`|createCompatibleDestImage|Takes 2 args. Method in class java.awt.image.RescaleOp  Creates a zeroed destination image with the correct size and number of  bands. |
|`createCompatibleDestRaster()`|createCompatibleDestRaster|Takes 0 args. Method in class java.awt.image.RescaleOp  Creates a zeroed-destination Raster with the correct  size and number of bands, given this source. |
|`createCompatibleSampleModel(${1:int}, ${2:int})`|createCompatibleSampleModel|Takes 2 args. Method in class java.awt.image.SampleModel  Creates a SampleModel which describes data in this SampleModel's   format, but with a different width and height. |
|`createDataBuffer()`|createDataBuffer|Takes 0 args. Method in class java.awt.image.SampleModel  Creates a DataBuffer that corresponds to this SampleModel. |
|`createSubsetSampleModel()`|createSubsetSampleModel|Takes 0 args. Method in class java.awt.image.SampleModel  Creates a new SampleModel  with a subset of the bands of this  SampleModel. |
|`createCompatibleSampleModel(${1:int}, ${2:int})`|createCompatibleSampleModel|Takes 2 args. Method in class java.awt.image.SinglePixelPackedSampleModel  Creates a new SinglePixelPackedSampleModel with the specified  width and height. |
|`createDataBuffer()`|createDataBuffer|Takes 0 args. Method in class java.awt.image.SinglePixelPackedSampleModel  Creates a DataBuffer that corresponds to this  SinglePixelPackedSampleModel. |
|`createSubsetSampleModel()`|createSubsetSampleModel|Takes 0 args. Method in class java.awt.image.SinglePixelPackedSampleModel  This creates a new SinglePixelPackedSampleModel with a subset of the  bands of this SinglePixelPackedSampleModel. |
|`contentsLost()`|contentsLost|Takes 0 args. Method in class java.awt.image.VolatileImage  Returns true if rendering data was lost since last  validate call. |
|`createGraphics()`|createGraphics|Takes 0 args. Method in class java.awt.image.VolatileImage  Creates a Graphics2D, which can be used to draw into  this VolatileImage. |
|`createWritableChild(${1:int}, ${2:int}, ${3:int}, ${4:int}, ${5:int}, ${6:int}, ${7:int[]})`|createWritableChild|Takes 7 args. Method in class java.awt.image.WritableRaster  Returns a new WritableRaster which shares all or part of this  WritableRaster's DataBuffer. |
|`createWritableTranslatedChild(${1:int}, ${2:int})`|createWritableTranslatedChild|Takes 2 args. Method in class java.awt.image.WritableRaster  Create a WritableRaster with the same size, SampleModel and DataBuffer  as this one, but with a different location. |
|`create(${1:RenderContext}, ${2:ParameterBlock})`|create|Takes 2 args. Method in interface java.awt.image.renderable.ContextualRenderedImageFactory  Creates a rendering, given a RenderContext and a ParameterBlock  containing the operation's sources and parameters. |
|`clone()`|clone|Takes 0 args. Method in class java.awt.image.renderable.ParameterBlock  Creates a copy of a ParameterBlock. |
|`clone()`|clone|Takes 0 args. Method in class java.awt.image.renderable.RenderContext  Makes a copy of a RenderContext. |
|`concatenateTransform()`|concatenateTransform|Takes 0 args. Method in class java.awt.image.renderable.RenderContext  Modifies the current user-to-device transform by appending another  transform. |
|`createDefaultRendering()`|createDefaultRendering|Takes 0 args. Method in interface java.awt.image.renderable.RenderableImage  Returnd a RenderedImage instance of this image with a default  width and height in pixels. |
|`createRendering()`|createRendering|Takes 0 args. Method in interface java.awt.image.renderable.RenderableImage  Creates a RenderedImage that represented a rendering of this image  using a given RenderContext. |
|`createScaledRendering(${1:int}, ${2:int}, ${3:RenderingHints})`|createScaledRendering|Takes 3 args. Method in interface java.awt.image.renderable.RenderableImage  Creates a RenderedImage instance of this image with width w, and  height h in pixels. |
|`createDefaultRendering()`|createDefaultRendering|Takes 0 args. Method in class java.awt.image.renderable.RenderableImageOp  Gets a RenderedImage instance of this image with a default  width and height in pixels. |
|`createRendering()`|createRendering|Takes 0 args. Method in class java.awt.image.renderable.RenderableImageOp  Creates a RenderedImage which represents this  RenderableImageOp (including its Renderable sources) rendered  according to the given RenderContext. |
|`createScaledRendering(${1:int}, ${2:int}, ${3:RenderingHints})`|createScaledRendering|Takes 3 args. Method in class java.awt.image.renderable.RenderableImageOp  Creates a RenderedImage instance of this image with width w, and  height h in pixels. |
|`create(${1:ParameterBlock}, ${2:RenderingHints})`|create|Takes 2 args. Method in interface java.awt.image.renderable.RenderedImageFactory  Creates a RenderedImage representing the results of an imaging  operation (or chain of operations) for a given ParameterBlock and  RenderingHints. |
|`clone()`|clone|Takes 0 args. Method in class java.awt.print.PageFormat  Makes a copy of this PageFormat with the same  contents as this PageFormat. |