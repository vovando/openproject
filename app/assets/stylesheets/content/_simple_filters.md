# Simple filters

Simple filters are forms that serve the purpose of limiting the number of entries in a list. As opposed to advanced filters however, there is no operator selection to search with.

By default, simple filters have a two columned layout.

```
@full-width

<fieldset class="simple-filters--container">
  <legend>Simple Filters</legend>
  <ul class="simple-filters--filters">
    <li class="simple-filters--filter">
      <label for="filter-1" class="simple-filters--filter-name">Project</label>
      <div class="simple-filters--filter-value">
        <input id="filter-1" type="text" placeholder="select">
      </div>
    </li>
    <li class="simple-filters--filter">
      <label for="filter-2" class="simple-filters--filter-name">Status</label>
      <div class="simple-filters--filter-value">
        <select id="filter-2" class="simple-filters--select">
          <option value="=" label="Active" selected="selected">Active</option>
          <option value="!" label="Archived">Archived</option>
          <option value="!*" label="All">all</option>
        </select>
      </div>
    </li>
  </ul>
  <div class="simple-filters--controls">
    <a class="button -highlight -small" href="#">Apply</a>
    <a class="button -small icon icon-undo" href="#">Clear</a>
  </div>
</fieldset>
```

If desired, the simple filter can have three columns.

```
@full-width

<fieldset class="simple-filters--container">
  <legend>Simple Filters</legend>
  <ul class="simple-filters--filters -columns-3">
    <li class="simple-filters--filter">
      <label for="filter-1" class="simple-filters--filter-name">Project</label>
      <div class="simple-filters--filter-value">
        <input id="filter-1" type="text" placeholder="select">
      </div>
    </li>
    <li class="simple-filters--filter">
      <label for="filter-2" class="simple-filters--filter-name">Status</label>
      <div class="simple-filters--filter-value">
        <select id="filter-2" class="simple-filters--select">
          <option value="=" label="Active" selected="selected">Active</option>
          <option value="!" label="Archived">Archived</option>
          <option value="!*" label="All">all</option>
        </select>
      </div>
    </li>
    <li class="simple-filters--filter">
      <label for="filter-3" class="simple-filters--filter-name">Name</label>
      <div class="simple-filters--filter-value">
        <select id="filter-3" class="simple-filters--select">
          <option value="=" label="Active" selected="selected">Active</option>
          <option value="!" label="Archived">Archived</option>
          <option value="!*" label="All">all</option>
        </select>
      </div>
    </li>
  </ul>
  <div class="simple-filters--controls">
    <a class="button -highlight -small" href="#">Apply</a>
    <a class="button -small icon icon-undo" href="#">Clear</a>
  </div>
</fieldset>
```
