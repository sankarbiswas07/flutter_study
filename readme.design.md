
**App Structure and Layout:**

-   `Scaffold`: App structure with app bar, body, and more.
    -   `appBar`, `body`, `floatingActionButton`, `bottomNavigationBar`, `drawer`
-   `AppBar`: Top bar with title, actions, and more.
    -   `title`, `actions`, `backgroundColor`
-   `BottomNavigationBar`: Bottom navigation bar with tabs.
    -   `items`, `onTap`
-  `TabBarView`: Swipeable tab bar content view.
    -   `controller`, `tabs`

**Widgets and Components:**

-   `Text`: Displays text with customizable style.
    -   `style`, `textDirection`
-   `Image`: Displays images from various sources.
    -   `image`, `fit`, `alignment`
-   `IconButton`: Icon button for actions in the app bar.
    -   `icon`, `onPressed`
-   `TextField`: User text input with customization.
    -   `controller`, `keyboardType`, `onSubmitted`
-   `ListView`: Scrollable lists of widgets.
    -   `children`, `scrollDirection`
-   `Card`: Material design card with content.
    -   `elevation`, `shape`, `child`

**Styling and Theming:**

-   `TextStyle`: Customizes text styles for consistency.
    -   `fontSize`, `fontWeight`, `color`
-   `Color`: Defines colors to maintain a theme.
    -   `Color(0xFFRRGGBB)`, `Colors.red`
-   `Theme`: Wraps the app with a theme and customizes it.
    -   `data`, `textTheme`, `textTheme.bodyText1`
-   `BoxDecoration`: Adds decorations to containers.
    -   `color`, `borderRadius`, `boxShadow`
-   `Padding`: Provides space around a widget.
    -   `padding`, `EdgeInsets.all(16.0)`

**Interaction and Navigation:**

-   `GestureDetector`: Adds touch interaction to widgets.
    -   `onTap`, `onLongPress`
-   `Navigator`: Manages app navigation between screens.
    -   `push`, `pop`
-   `PageRoute`: Customizes page transitions.
    -   `PageView`, `CupertinoPageRoute`
-   `InkWell`: Provides Material Design touch feedback.
    -   `onTap`, `highlightColor`
-   `PageRouteBuilder`: Creates custom page transitions.
    -   `transitionsBuilder`, `duration`

**Responsiveness:**

-   `MediaQuery`: Accesses screen dimensions and orientation.
    -   `size`, `orientation`, `devicePixelRatio`
-   `LayoutBuilder`: Builds widgets based on layout constraints.
    -   `builder`
-   `Flexible`: Creates flexible layouts in a `Row` or `Column`.
    -   `flex`
-   `Expanded`: Expands widgets within a `Row` or `Column`.
    -   `flex`
-   `Wrap`: Wraps widgets within a parent widget.
    -   `alignment`, `direction`

**State Management:**

-   `StatefulWidget`: Manages mutable state.
    -   `setState`, `build`
-   `StatelessWidget`: Represents immutable components.
    -   `build`
-   `Provider`: Manages app-wide state.
    -   `Provider.of`, `ChangeNotifierProvider`
-   `Bloc`: Implements business logic and state management.
    -   `BlocProvider`, `BlocBuilder`
-   `GetX`: Provides reactive state management.
    -   `GetBuilder`, `Obx`

**Lists and Grids:**

-   `ListView`: Scrollable lists of widgets.
    -   `children`, `scrollDirection`
-   `GridView`: Displays widgets in a grid format.
    -   `gridDelegate`, `crossAxisCount`
-   `SliverList`: Builds scrollable lists for custom scroll views.
    -   `SliverChildBuilderDelegate`, `itemExtent`
-   `SliverGrid`: Constructs grid views for custom scroll views.
    -   `gridDelegate`, `delegate`

**Animations and Transitions:**

-   `AnimatedContainer`: Animates container properties.
    -   `duration`, `curve`
-   `Hero`: Creates hero animations between screens.
    -   `tag`, `flightShuttleBuilder`
-   `PageRouteBuilder`: Customizes page transitions.
    -   `pageBuilder`, `transitionsBuilder`
-   `TweenAnimationBuilder`: Animates values over a range.
    -   `tween`, `builder`
-   `StaggeredAnimationBuilder`: Delays animations in a sequence.
    -   `delay`, `duration`

**Alignment and Positioning:**

-   `Align`: Aligns a child within its parent widget.
    -   `alignment`, `widthFactor`, `heightFactor`
-   `Positioned`: Positions a child within a `Stack`.
    -   `left`, `right`, `top`, `bottom`
-   `Align`: Aligns a child within its parent widget.
    -   `alignment`, `widthFactor`, `heightFactor`
-   `Positioned`: Positions a child within a `Stack`.
    -   `left`, `right`, `top`, `bottom`
-   `FractionallySizedBox`: Sizes a child as a fraction of its parent.
    -   `widthFactor`, `heightFactor`
-   `Row` and `Column`: Positions children horizontally or vertically.
    -   `mainAxisAlignment`, `crossAxisAlignment`
-   `Expanded`: Expands a child in a `Row` or `Column`.
    -   `flex`
-   `Container`: Adds padding, margin, and alignment.
    -   `padding`, `margin`, `alignment`
-   `Padding`: Adds space around a child widget.
    -   `padding`
-   `SizedBox`: Sizes a child widget with specific dimensions.
    -   `width`, `height`
-   `Flexible`: Creates flexible layouts in a `Row` or `Column`.
    -   `flex`
-   `ConstrainedBox`: Enforces constraints on a child widget.
    -   `constraints`
-   `Wrap`: Wraps widgets within a parent widget.
    -   `alignment`, `spacing`, `runSpacing`
-   `Center`: Centers a child within its parent.
    -   `child`
-   `Align`: Aligns a child within its parent widget.
    -   `alignment`, `widthFactor`, `heightFactor`
-   `Positioned`: Positions a child within a `Stack`.
    -   `left`, `right`, `top`, `bottom`
-   `FractionallySizedBox`: Sizes a child as a fraction of its parent.
    -   `widthFactor`, `heightFactor`
-   `Row` and `Column`: Positions children horizontally or vertically.
    -   `mainAxisAlignment`, `crossAxisAlignment`
-   `Expanded`: Expands a child in a `Row` or `Column`.
    -   `flex`
-   `Container`: Adds padding, margin, and alignment.
    -   `padding`, `margin`, `alignment`
-   `Padding`: Adds space around a child widget.
    -   `padding`
-   `SizedBox`: Sizes a child widget with specific dimensions.
    -   `width`, `height`
-   `Flexible`: Creates flexible layouts in a `Row` or `Column`.
    -   `flex`
-   `ConstrainedBox`: Enforces constraints on a child widget.
    -   `constraints`
-   `Wrap`: Wraps widgets within a parent widget.
    -   `alignment`, `spacing`, `runSpacing`
-   `Center`: Centers a child within its parent.
    -   `child`
