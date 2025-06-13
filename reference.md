# Reference
## StyleGuides
<details><summary><code>client.style_guides.<a href="src/acrolinx/style_guides/client.py">get_style_guides</a>()</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from acrolinx import acrolinx

client = acrolinx(
    api_key="YOUR_API_KEY",
    base_url="https://yourhost.com/path/to/api",
)
client.style_guides.get_style_guides()

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.style_guides.<a href="src/acrolinx/style_guides/client.py">create_style_guide</a>()</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from acrolinx import acrolinx

client = acrolinx(
    api_key="YOUR_API_KEY",
    base_url="https://yourhost.com/path/to/api",
)
client.style_guides.create_style_guide()

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.style_guides.<a href="src/acrolinx/style_guides/client.py">get_style_guide</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from acrolinx import acrolinx

client = acrolinx(
    api_key="YOUR_API_KEY",
    base_url="https://yourhost.com/path/to/api",
)
client.style_guides.get_style_guide(
    style_guide_id="style_guide_id",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**style_guide_id:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.style_guides.<a href="src/acrolinx/style_guides/client.py">update_style_guide</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from acrolinx import acrolinx

client = acrolinx(
    api_key="YOUR_API_KEY",
    base_url="https://yourhost.com/path/to/api",
)
client.style_guides.update_style_guide(
    style_guide_id="style_guide_id",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**style_guide_id:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.style_guides.<a href="src/acrolinx/style_guides/client.py">delete_style_guide</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from acrolinx import acrolinx

client = acrolinx(
    api_key="YOUR_API_KEY",
    base_url="https://yourhost.com/path/to/api",
)
client.style_guides.delete_style_guide(
    style_guide_id="style_guide_id",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**style_guide_id:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## StyleChecks
<details><summary><code>client.style_checks.<a href="src/acrolinx/style_checks/client.py">create_style_check</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from acrolinx import acrolinx

client = acrolinx(
    api_key="YOUR_API_KEY",
    base_url="https://yourhost.com/path/to/api",
)
client.style_checks.create_style_check(
    document_id="document_id",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**document_id:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.style_checks.<a href="src/acrolinx/style_checks/client.py">get_style_check</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from acrolinx import acrolinx

client = acrolinx(
    api_key="YOUR_API_KEY",
    base_url="https://yourhost.com/path/to/api",
)
client.style_checks.get_style_check(
    workflow_id="workflow_id",
    document_id="document_id",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**workflow_id:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**document_id:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## StyleSuggestions
<details><summary><code>client.style_suggestions.<a href="src/acrolinx/style_suggestions/client.py">create_style_suggestion</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from acrolinx import acrolinx

client = acrolinx(
    api_key="YOUR_API_KEY",
    base_url="https://yourhost.com/path/to/api",
)
client.style_suggestions.create_style_suggestion(
    document_id="document_id",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**document_id:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.style_suggestions.<a href="src/acrolinx/style_suggestions/client.py">get_style_suggestion</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from acrolinx import acrolinx

client = acrolinx(
    api_key="YOUR_API_KEY",
    base_url="https://yourhost.com/path/to/api",
)
client.style_suggestions.get_style_suggestion(
    workflow_id="workflow_id",
    document_id="document_id",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**workflow_id:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**document_id:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## StyleRewrites
<details><summary><code>client.style_rewrites.<a href="src/acrolinx/style_rewrites/client.py">create_style_rewrite</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from acrolinx import acrolinx

client = acrolinx(
    api_key="YOUR_API_KEY",
    base_url="https://yourhost.com/path/to/api",
)
client.style_rewrites.create_style_rewrite(
    document_id="document_id",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**document_id:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.style_rewrites.<a href="src/acrolinx/style_rewrites/client.py">get_style_rewrite</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from acrolinx import acrolinx

client = acrolinx(
    api_key="YOUR_API_KEY",
    base_url="https://yourhost.com/path/to/api",
)
client.style_rewrites.get_style_rewrite(
    workflow_id="workflow_id",
    document_id="document_id",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**workflow_id:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**document_id:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

