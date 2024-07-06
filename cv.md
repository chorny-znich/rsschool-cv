# Dzmitry Tarhonski

## Contacts

- E-mail: vargar.dt@gmail.com
- GitHub: chorny-znich

## Skills

- C++
- HTML & CSS
- JavaScript

## Code examples

```
	template <typename Id, typename Asset>
	void AssetManager<Id, Asset>::load(Id id, const std::string& filename) {
		std::unique_ptr<Asset> pAsset = std::make_unique<Asset>();
		if (!pAsset->loadFromFile(filename)) {
			throw std::runtime_error("Failed to load asset from " + filename);
		}
		auto iter = mAssets.insert(std::make_pair(id, std::move(pAsset)));
		assert(iter.second);
	}
```

## Education

- Brest State A. Pushkin University
  - Physics and computer science

## Courses

- Coursera
  - Specialization "C++ Development Basics"
- RSSchool
  - JavaScript/Front-end

## Language

- English: level - A2
