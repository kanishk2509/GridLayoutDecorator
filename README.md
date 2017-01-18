# GridLayoutDecorator
A simple Java class to evenly space out GridLayout (as seen in Android RecyclerView) items.

// initialize your recycler view

recyclerView = (RecyclerView) findViewById(R.id.rcview);

recyclerView.setHasFixedSize(true);

recyclerView.setLayoutManager(new StaggeredGridLayoutManager(2,1));

int spanCount = 2; // 2 columns

int spacing = 5; // 50px

boolean includeEdge = true;

recyclerView.addItemDecoration(new GridItemDecoration(spanCount, spacing, includeEdge));


# Voila! There you go.
